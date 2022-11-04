# Strings 

Draco corelib will not use, or expose .NET System.String as the default string reprensation.  

This is motived by the fact that System.Strings are encoded in UTF16, and the industry has since chosen UTF-8 as THE standard for text encoding.
.NET itself want to add an Utf8String: https://github.com/dotnet/runtime/issues/933

Additional reading:  
https://developer.apple.com/documentation/swift/string
