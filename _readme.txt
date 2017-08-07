Shawn Halayka
shalayka@gmail.com
Oct 1, 2011




A graphical application that views the HadCRUT3 temperature data. Uses TetGen and OpenGL/GLUT libraries.

See http://code.google.com/p/hadcrut3-july-2011-viewer/downloads/list

The app and source code are in the public domain.

For more information on the data ("station record files"), see:
- http://www.metoffice.gov.uk/research/climate/climate-monitoring/land-and-atmosphere/surface-station-records

And "P. Brohan, J.J. Kennedy, I. Harris, S.F.B. Tett and P.D. Jones, Uncertainty estimates in regional and global observed temperature changes: a new dataset from 1850. J. Geophys. Res, 111, D12106, doi:10.1029/2005JD006548":
- http://www.metoffice.gov.uk/hadobs/crutem3/HadCRUT3_accepted.pdf

And Luboš Motl's blog posts on the data:
- http://motls.blogspot.com/2011/07/hadcrut3-raw-data-released.html
- http://motls.blogspot.com/2011/08/hadcrut3-annual-mean-temperatures-and.html
- http://motls.blogspot.com/2011/07/hadcrut3-30-of-stations-recorded.html 




Version log:
1.0 -- Original release
1.01 -- Added viewing of warming/cooling linear trends. Changed linear trend code to only accept trends with a minimum of 20 samples.
1.02 -- Added option to raise or lower the number of minimum samples needed for an acceptable trend. See note directly above.
1.03 -- Added global min, mean, max temp, and global min, max trend to display. Reduced display font size.




This zip file includes:

- hadcrut3_to_binary_1.0.zip:
  A Win32 console app and Win32-specific C++ source code for converting
  the original HadCRUT3 text files into a single HadCRUT3 binary file.

  The original HadCRUT3 text files for July 2011 can be obtained at: 
  http://www.metoffice.gov.uk/media/zip/e/0/station_files.20110720.zip


- hadcrut3_viewer_1.0_source.zip:
  A cross-platform C++ source code for viewing the HadCRUT3 binary file.


- hadcrut3_viewer.exe:
  A Win32 app for viewing the HadCRUT3 binary file.


- glut32.dll:
  Library file required by hadcrut3_viewer.exe.


- HadCRUT3.bin:
  The HadCRUT3 binary file, pre-generated for your convenience from the
  original HadCRUT3 text files for July 2011.
