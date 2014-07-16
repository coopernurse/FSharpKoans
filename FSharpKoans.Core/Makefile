
all:
	mkdir -p bin
	fsharpc KoanAttribute.fs Helpers.fs KoanResult.fs KoanContainer.fs KoanRunner.fs \
	  -r packages/NUnit.2.5.10.11092/lib/nunit.framework.dll --target:library -o bin/FSharpKoans.Core.dll

deps:
	nuget install NUnit -Version 2.5.10.11092 -OutputDirectory packages

