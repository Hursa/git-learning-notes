# GO LANG

* What is the source tree of GO?
  - $GOPATH
    + ***src***: the source code the echo projects. Each project has its own dir in $GOPATH/src/
    + ***pkg***: containing the .a files you complie from the src codes
    + ***bin***: containing the excutable files compiled from the src codes

* What is the path GOPATH for? We must set GOPATH which contains the source code of our orjects. But can we put our source code to other sources?

When using go install pak_name, it will search the $GOPATH/src/pkg_name directories. 
