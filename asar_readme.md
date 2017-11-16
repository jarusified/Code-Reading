Asar is an archive format used by electron. (Better tar ?)

* Tar archive utility doesn't really compress the files. Rather it only collects files and their metadata together and produce a single file. It just archives.
* Asar adds random access ability to the tar utilities. Tar doesnt have a centralized location for the information about the contents of the file. So to list the names of the file, one must read through the entire archive and look address by address.

** Libraries used

* Commander - for Command line help and to organize actions for the script.
* minimatch - Matching library for converting glob expressions to Javascript RegEx objects.
* tmp - used for creating temporary files.

for..of statement is used for iterating over iterable objects(Array, Map, Set, String, TypedArray)

TypedArray (feature in ES17): [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray].
* Array like view for binary data buffer. 