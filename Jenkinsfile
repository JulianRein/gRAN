@Library('R-build-pipeline')
//import DXREB_Rbuild not needed without packages/subfolders in shared libary

//ONLY change values here! Must be defined with this variable names to work.
pkg2build="GRANBase" //must be identical to workplace-subdir created by jenkins and pkgName in R
srcDir=""
testDir=null //"TC-Collection/Main/automated-TCs/"
r_versions="R-3.4.2" //space-separated

def pipeline=new DXREB_Rbuild()
pipeline.startBuildProcess(pkg2build,srcDir,testDir, r_versions)
