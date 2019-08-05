
These files take SIF files from Voyager and produce files ready for import to Alma.  We rewrite the fixed-length SIF file into XML.

- **sis2alma.pl** - converts our student information system records for Alma import.
- **hr2alma.pl** - converts our HR (faculty & staff) records for Alma import.
- **findthegrads.sh** - a shell script that deletes from the HR file anyone that's a grad student in the SIS file.  

The findthegrads script is explained at <https://inodeblog.com/?p=1710>


