# android442Hook
init commit code

/************************************************/


School : University of Science and  Technology of China (U.S.T.C)


Student NO : SA16225432


Author : zhangqijun


E-Mail : sa516432@mail.ustc.edu.cn


/*************************************************/



/*********************************************************************************************************************/



                     Based on the framework of Xposed
     
              And Hook the packageInstaller named com.android.packageinstaller


/*********************************************************************************************************************/ 


The installerpackage used follow as:


1\PackageInstallerActivity.java


    |---Method : startInstallConfirm();


2\PackageUtil.java


    |---Method : getAppSnippet(Activity,ApplicationInfo,Uri);


    |---Method : getPackageInfo(Uri);
    
packageinstaller source code URL:


      https://github.com/cubieboard/openbox_packages_apps_PackageInstaller


-------------------------------------------------------------------------------------------------------


Develop Environment:MIUI V5



Android Version  4.4.2
