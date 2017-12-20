# hello-world
wibble wibble
and a little bit of code
$systemEntries=gwmi win32_system
foreach($systemEntry in $systemEntries){write-host $systemEntry.Name}
