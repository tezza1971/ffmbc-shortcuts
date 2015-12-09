# ffmbc-shortcuts
This is a library of shell commands for moderately lazy people who aren't afraid of the command line, but couldn't be bothered remembering a gazillion esoteric options for ffmbc just to get some work done.

ffmbc is a derivative of ffmpeg command line utility for transcoding various audio/video assets from one format to another (amongst other things). Since codecs are intrinsically complex, and the needs of users are always varied, there is not much chance of making such a tool without have an explosion of options and parameters. Unfortunately, finding out which ones to use can be a painful process. A GUI can help a lot, but then that negates the flexibility and utility of being able to call up processing from the command line.

To that end, the scripts in this library can be seen as shortcuts to achieve a task quickly without having to do too much reading. And if the shortcut script doesn't fit your needs exactly, you can use it as a starting template to make your own variant for later use.

To that end, the scripts generally take a minimalist approach (in so far as this is possible) and attempt to rely on default values where reasonable to do so.

At the top level, there are separate folders for DOS(Windows, *.bat files) and Unix(Linux and Mac OSX, *.sh files).

Under that, there are separate folders which act as a guide for the major problem domains for transcoding video;
  * INTERMEDIATE for creating intermediate files to be used on the NLE timeline
  * EXPORT for creating the most compressed files to be used on the Internet. This often represents the final output.
