# orthanc-extract-document
Orthanc-extract-document gives access to hidden reports generated and stored by OsiriX and Horos reporting tool, using EncapsulatedDocument feature and zip container 

#
Osirix MD and [@Horos ](https://github.com/horosproject/horos/) support reporting using MacOS compatibile text editors, i.e. Pages, LibreOffice, Microsoft Word, TextEdit, and Osirix HTML Editor. 

The reports are stored as files in /Reports directory in Osirix/Horos Data folder. 

They are sent as DICOM encapsulated documents (0042,0011 EncapsulatedDocument) between Horos/Osirix nodes - reports sent are properly imported and added to patient list. 

It is always DICOM embedded ZIP container, containing a single (?) file, in a file format used natively by the text editor chosen in "Database" settings tab in Osirix/Horos. 

The plugin gives user direct access to the content of the zip file stored as EncapsulatedDocument. 

No other known use case of ZIP-in-DICOM embedding is known to the author. 
