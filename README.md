# GO
Tutorial to launch the Go language and write a simple Hello World Program :


# On Windows 10 :


  - Download and execute the environment archive on the golang website https://golang.org/dl/
  
  
  - Under Windows, you may set environment variables through the "Environment Variables" button on the "Advanced" tab of the "System"    control panel. Some versions of Windows provide this control panel through the "Advanced System Settings" option inside the "System" control panel.
  
  
  - Create your workspace directory, %USERPROFILE%\go. (If you'd like to use a different directory, you will need to set the GOPATH environment variable.)
  
  
  - Next, make the directory src/hello inside your workspace, and in that directory create a file named hello.go that looks like:

        package main

        import "fmt"

        func main() {
          fmt.Printf("hello, world\n")
        }
      
      
 - Then build it with the go tool : go build in the command prompt 
 
 
 - Execute the binary : ./YourEx.exe 
 
 
 # On Linux and MacOS :
   - Download the Linux or MacOS archive of the go website https://golang.org/dl/
   
   
   - extract it 
            
            tar -xzf yourfile.tar.gz
      
   
   - Add /usr/local/go/bin to the PATH environment variable. You can do this by adding this line to your /etc/profile (for a system-wide        installation) or $HOME/.profile:
   
      export PATH=$PATH:/usr/local/go/bin
   
   
   - then follow the instructions from step 3 windows 10
    
