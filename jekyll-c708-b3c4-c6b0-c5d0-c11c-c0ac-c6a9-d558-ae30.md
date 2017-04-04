##### 소개

Jekyll을 사용하려고 보니 아래와 같이 GUN/Linux, Unix, or macOS 에서 사용하라고 되어 있다.

하지만, 아래 추가적인 내용을 살펴보니. window에서도 충분히 사용 가능해 보인다.

즉 Requirements만 만족하면 window에서 구동 가능해 보인다.

그래서, window에서 Jekyll을 사용하는 방법을 살펴 보고 소개한다.

![](/assets/jekyll-requirements.png)



* Ruby
* Ruby development headers
* RubyGems \(Ruby 설치하면 같이 설치됨\)
* NodeJs
* Python 2.7



##### Ruby 설치

ruby window용 설치가 지원된다. 아래 사이트에서 다운 받아 설치한다.

[https://rubyinstaller.org/downloads/](https://rubyinstaller.org/downloads/)

![](/assets/window-ruby-install.png)

최신 버전으로 설치, 자신의 os 아키텍쳐에 맞는 버전으로 설치한다. 64bit쓰면 x64로

![](/assets/ruby-check.png)

정상 설치되었는지 'ruby --version' 으로 확인 가능하다.

만약 command에러가 나는 경우, window에 PATH 정보에 ruby PATH 정보를 추가한다.

기본적으로 설치시 PATH 옵션을 설정하였다면, 문제 없이 버전 정보를 볼 수 있다.



##### Ruby development headers 설치

ruby development headers는 ruby development kit을 설치하면 된다.

아래 사이트에서 다운 받아서 압축을 해제 한다.

[https://rubyinstaller.org/downloads/](https://www.gitbook.com/book/gseok/web-technology-introduction/edit#)

![](/assets/ruby-dev-kit-install.png)

설치위 위에서 설치한 ruby 버전에 맞는 버전으로 설치한다. ruby development kit의 설치 방법은

[https://github.com/oneclick/rubyinstaller/wiki/Development-Kit](https://github.com/oneclick/rubyinstaller/wiki/Development-Kit) 에 잘 설명되어 있다. Quick guide에 따라

압축 해제한 디렉토리에 가서 다음 명령어를 수행한다.

```ruby
ruby dk.rb init
ruby dk.rb install
```

아래와 같이 출력되면 정상 설치된 것이다.

![](/assets/ruby-dev-kit-install-success.png)



##### Node.js 설치

[https://nodejs.org/en/](https://nodejs.org/en/)

![](/assets/node.js-install.png)

사이트에서 최신 버전이나 LTS버전을 받아 설치한다.

아래와 같이 출력되면 정상 설치된 것이다.

![](/assets/node-js-install-check.png)



Python 2.7 설치

[https://www.python.org/downloads/](https://www.python.org/downloads/)




