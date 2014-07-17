
all:
	mkdir -p bin
	fsharpc KoanAttribute.fs Helpers.fs KoanResult.fs KoanContainer.fs KoanRunner.fs \
	  -r packages/NUnit.2.6.3/lib/nunit.framework.dll \
	  --target:library \
	  -o bin/FSharpKoans.Core.dll

deps:
	rm -rf packages
	mkdir -p packages
	nuget install NUnit -Version 2.6.3 -OutputDirectory packages
	gacutil -i packages/NUnit.2.6.3/lib/nunit.framework.dll

