# animation-assembler:  

Uses wine to run Circles' Animation Assembler.  

## Usage:

Run on the bin file you want to assemble. This is for assembling one file.  
Run with the -r argument to search all directories from current directory onwards for bin files to assemble.  
  (If there are move than 100 bin files found, the script will stop. The dangerous version has no such restriction)  
  
# PNG2Dmp:  

Uses wine to run Png2Dmp (As of writing this I don't know who the creator is)

## Usage:

Run on the png file you want to compress. This is for compressing one file.  
Run with the -r argument in place of a file name to search all directories from current directory onwards for png files to compress  
  (If there are move than 100 bin files found, the script will stop. The dangerous version has no such restriction)  
Run with the --move argument to automatically move the output files to the location specified in the DMP_DIR variable  
All normal Png2Dmp commands work with this script as long as they come after -r (or --move if it is present).  

# portrait-formatter:

Uses wine to run Portrait Formatter by Crazycolerz5  

## Usage:

Run on the png file you want to format.  
The -r and --move arguments work the same here as they do in PNG2Dmp
