# The Images -> /img/ and /img_resources/

img_resources are the original png or svg files - the folder is stored in git, but not deployed
the img_resoures files are automatically reformatted based on their sizes with a jenkins script as part of the build
if the files are already available they will not be converted