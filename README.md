# HOTWIRE GETTING STARTED PROJECT
This project explores popular [Hotwire/Turbo/Stimulus](https://hotwired.dev) features. These are a set of techniques that make a dynamic webpage without any Javascript. It uses Websocket to updating the page dynamically. _Stimulus_ is the [most used](https://railsdeveloper.com/survey/2024/#javascript-rails) Javascript framework in the Rails ecosystem. 

> Although very interesting and easy to use, note that _Stimulus_ is [not event mentioned](https://survey.stackoverflow.co/2024/technology/#most-popular-technologies) in the StackOverflow survey!

## Project Overview
The project is entirely based on [website tutorial](https://hotwired.dev), mimicking a chat room with `room` and `message` as the main application elements. The application is created as a standard rails app. Then, Hotwire features are added.

After the standard Rails application is working, these are the steps to add Hotwire features: 
1. [To add dependencies](https://github.com/gabrielcostasilva/rails-hotwire-getting-started/commit/9dbce8a9fdbf010fd1ad40e6a040cb86e67c6302)
2. [To install Hotwire](https://github.com/gabrielcostasilva/rails-hotwire-getting-started/commit/63ec4b09f300ae9d175fd58a3f9386cce6b9658d) with `bin/rails hotwire:install`
3. [To wrap `room` in a Turbo frame](https://github.com/gabrielcostasilva/rails-hotwire-getting-started/commit/84f8c176ea7da4908758f2ebc00003fde3b34ba5). This these are going to be the dynamic components.
4. [To set `message` lazy load](https://github.com/gabrielcostasilva/rails-hotwire-getting-started/commit/08340706b937408109dec2b7d3c47cc11a6f7839)
5. [To handle DOM update](https://github.com/gabrielcostasilva/rails-hotwire-getting-started/commit/96dfbd7e216ff6f660105c5df99ac0557cf02749)
6. [To add Stimulus controller](https://github.com/gabrielcostasilva/rails-hotwire-getting-started/commit/2a79230d11d1b124a0b28b25e3264402147326a2)
7. [To add Websocket](https://github.com/gabrielcostasilva/rails-hotwire-getting-started/commit/f4bc5bf0c38ec08d4be098f30002ab87189bd6ec)


## References
- [Official website](https://hotwired.dev)
- [Article #1](https://www.hotrails.dev/articles/rails-modals-with-hotwire)
- [Article #2](https://cycode.com/blog/how-to-build-modals-with-hotwire-turbo-frames-stimulusjs/)