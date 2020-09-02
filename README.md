你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# gb

[![wercker status](https://app.wercker.com/status/494a8ac6b836f39cc7e67036d957a43e/m "wercker status")](https://app.wercker.com/project/bykey/494a8ac6b836f39cc7e67036d957a43e)

`gb` is a proof of concept replacement build tool for the [Go programming language](https://golang.org).

I gave a talk about `gb` and the rational for its creation at GDG Berlin in April 2015, [video](https://www.youtube.com/watch?v=c3dW80eO88I) and [slides](http://go-talks.appspot.com/github.com/davecheney/presentations/reproducible-builds.slide#1).

## Project based

`gb` operates on the concept of a project. A gb project is a workspace for all the Go code that is required to build your project.

A gb project is a folder on disk that contains a subdirectory named <code>src/</code>. That's it, no environment variables to set. For the rest of this document we'll refer to your <code>gb</code> project as <code>$PROJECT</code>.

You can create as many projects as you like and move between them simply by changing directories.

## Installation

    go get github.com/constabulary/gb/...

## Read more

gb has its own site, [getgb.io](http://getgb.io/), head over there for more information.
