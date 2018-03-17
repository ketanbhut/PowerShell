<#
.Synopsis
   Creates folder structure at the target backup location and copies Desktop, Documents and Favorities from User's profile

.DESCRIPTION
   Takes a target variable targetFolder, to be the parent backup location. Feel free to modify as needed. 
   Creates folder structure under targetFolder in YYYY_MMM_DD_HH.MM format and creates Desktop, Documents and Favorities folders
   All files are copied under their respective folders in exact folder structure. 
   
    Script by         : Ketan Thakkar (KetanBhut@live.com)
    Script version    : 1.0
    Release date      : 17-Mar-2018
    Disclaimer        : This script is tested and working in my environment, 
                        it is recommended that you test it in a test environment 
                        before using in your production environment
#>
