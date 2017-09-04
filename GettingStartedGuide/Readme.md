**Getting Started**


  Set Up Environment:
    
    1.    Download Jdk 8 , Install
    
        
    Windows:
            1.    set JAVA_HOME=C:\_appInstalled\jdk1.7.0_25
            2.    set path=%JAVA_HOME%\bin;%path%
            
    
    Unix:
            1.    export JAVA_HOME=C:\_appInstalled\jdk1.7.0_25
            2.    export PATH=%JAVA_HOME%\bin:%PATH%
                
    java -version  ( To Check Version )
        
    _FAQ_:    How can I tell if I'm running in 64-bit JVM or 32-bit JVM (from within a program)?
    
    Answers : java -d64 -version
              java -d32 -version
              
              Just type java -version in your console 
              If a 64 bit version is running, you'll get a message like:
              
              java version "1.6.0_18"
              Java(TM) SE Runtime Environment (build 1.6.0_18-b07)
              Java HotSpot(TM) 64-Bit Server VM (build 16.0-b13, mixed mode)
              
              A 32 bit version will show something similar to:
              
              java version "1.6.0_41"
              Java(TM) SE Runtime Environment (build 1.6.0_41-b02)
              Java HotSpot(TM) Client VM (build 20.14-b01, mixed mode, sharing)
              
              You can also use System.getProperty("sun.arch.data.model")  
                                                  	

  Two Modes : 

      1. Command Line
               javac Demo.java ( To Compile )
               java Demo ( To Run )

      2. IDE :  Use Intellij
        
   Version : 
      
      Build Tool : Maven ( 3.3.9 )
      JDK : 1.8
      
