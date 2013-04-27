ofxDirectoryWatcher
===================

A Directory Watcher Addon.

NOTE: Currently implemented with https://code.google.com/p/simplefilewatcher

Will use Poco::DirectoryWatcher as soon as the openFrameworks core moves past 1.4.6+

In order for mingw on windows to find CreateFile and CreateEvent, I had to define POCO_NO_UNWINDOWS in the build options of the project

http://pocoproject.org/docs/Poco.DirectoryWatcher.html
