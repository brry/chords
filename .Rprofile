
if(.Platform$OS.type=="unix") .libPaths("/home/berry/R/libBerry/")
if(requireNamespace("installB", quietly=TRUE))
{
 if(.Platform$OS.type=="unix") installB::loadPackages(ask=FALSE)
}
berryFunctions::combineFiles(inFiles=dir("OpenSong/Songs/", full=TRUE),
                             outFile=paste0("OpenSong/0_all_songs_",Sys.Date(),".txt"),
                             overwrite=TRUE)
