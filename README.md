Stuff I filled in as I learned ruby

#Useful Modules:
- Sinatra (For HTTP servers)
- rest-client (for access REST clients)
- active_support (for hashes and bits and bobs)
- Capistrano / Rake (for RPC stuff)

You can put a shebang at the start of an executable to make it go to ruby.

TIPS: 
JSON.parse(stuff) turns json into :name => "variable" hashes

ERROR CATCHING:
begin
   # -
rescue OneTypeOfException
   # -
rescue AnotherTypeOfException
   # -
else
   # Other exceptions
end

INPUTS ON ARGV ARRAY (ie ARGV[0])

puts puts out a string ;)

abort("string") quits with error message

code=ARGV[0]
code.nil? ? abort("Usage - provide a code as an argument") : nil

.class and .methods are useful in irb to check for things you can do on an object.
IF ALL ELSE FAILS GO ITERATIVE / OLD FASHIONED
SOMETIMES YOU CAN DO SOMETHING CLEVER BY REDEFINING CLASSES - BUT ONLY IF YOU HAVE TIME!
