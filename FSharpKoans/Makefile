
all:
	mkdir -p bin
	fsharpc AboutAsserts.fs \
    AboutLet.fs \
    AboutFunctions.fs \
    AboutTheOrderOfEvaluation.fs \
    AboutUnit.fs \
    AboutTuples.fs \
    AboutStrings.fs \
    AboutBranching.fs \
    AboutLists.fs \
    AboutPipelining.fs \
    AboutArrays.fs \
    AboutLooping.fs \
    MoreAboutFunctions.fs \
    AboutDotNetCollections.fs \
    AboutTheStockExample.fs \
    AboutRecordTypes.fs \
    AboutOptionTypes.fs \
    AboutDiscriminatedUnions.fs \
    AboutModules.fs \
    AboutClasses.fs \
    PathToEnlightenment.fs \
      --standalone \
	  -r ../FSharpKoans.Core/bin/FSharpKoans.Core.dll \
	  -I ../FSharpKoans.Core/packages/NUnit.2.6.3/lib \
	  --target:exe \
	  -o bin/FSharpKoans.exe

watch:
	wr --exec "make && mono bin/FSharpKoans.exe" *.fs