#### Windows 10 x86 (Visual Studio 2013 v12.0.40629.00 Update 5):
```
Running 498 test cases...
compiler: MSVC v18.00.40629
architecture: x86
__cpp_lib_string_view: 199711
sizeof wchar_t: 2
UTFW: UTF16
Resolution: 3400037433
UTF80 ==> UTF80: 0.121654629s
UTF80 ==> UTF16: 0.291160310s
UTF80 ==> UTF32: 0.167612008s
UTF80 ==> UTFW0: 0.291280529s
UTF16 ==> UTF80: 0.332530233s
UTF16 ==> UTF16: 0.068903233s
UTF16 ==> UTF32: 0.099845793s
UTF16 ==> UTFW0: 0.071755874s
UTF32 ==> UTF80: 0.292473052s
UTF32 ==> UTF16: 0.188609100s
UTF32 ==> UTF32: 0.037877509s
UTF32 ==> UTFW0: 0.188855093s
UTFW0 ==> UTF80: 0.338934002s
UTFW0 ==> UTF16: 0.071799853s
UTFW0 ==> UTF32: 0.101251856s
UTFW0 ==> UTFW0: 0.068184402s
codecvt_utf8_utf16<char16_t>:
UTF16 ==> UTF80: 0.613488208s (+84.49%)
UTF80 ==> UTF16: 0.407620557s (+40.00%)
codecvt_utf8_utf16<wchar_t>:
UTFW0 ==> UTF80: 0.607242966s (+79.16%)
UTF80 ==> UTFW0: 0.407731217s (+39.98%)

*** No errors detected
```
#### Windows 10 x64 (Visual Studio 2013 v12.0.40629.00 Update 5):
```
Running 498 test cases...
compiler: MSVC v18.00.40629
architecture: x64
__cpp_lib_string_view: 199711
sizeof wchar_t: 2
UTFW: UTF16
Resolution: 3400037414
UTF80 ==> UTF80: 0.115650676s
UTF80 ==> UTF16: 0.246199703s
UTF80 ==> UTF32: 0.138901067s
UTF80 ==> UTFW0: 0.248484383s
UTF16 ==> UTF80: 0.299133629s
UTF16 ==> UTF16: 0.061877892s
UTF16 ==> UTF32: 0.093623881s
UTF16 ==> UTFW0: 0.062121074s
UTF32 ==> UTF80: 0.253864031s
UTF32 ==> UTF16: 0.158999263s
UTF32 ==> UTF32: 0.038090847s
UTF32 ==> UTFW0: 0.138323250s
UTFW0 ==> UTF80: 0.322438254s
UTFW0 ==> UTF16: 0.062463203s
UTFW0 ==> UTF32: 0.093962848s
UTFW0 ==> UTFW0: 0.069426267s
codecvt_utf8_utf16<char16_t>:
UTF16 ==> UTF80: 0.542205702s (+81.26%)
UTF80 ==> UTF16: 0.384640892s (+56.23%)
codecvt_utf8_utf16<wchar_t>:
UTFW0 ==> UTF80: 0.540444676s (+67.61%)
UTF80 ==> UTFW0: 0.382421673s (+53.90%)

*** No errors detected
```