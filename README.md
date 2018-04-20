Wende
---
Wende(问得) Chinese Question Answering, is a small and simple factoid
chinese question answering system written in Python. You ask a chinese
natural language question and Wende will try to give a certain answer
of the question. This is still a work in progress, currently the system
can only judge the type of the question that the user ask, which means,
only the question classification module has been implemented.

## Run within Docker

1. Download and install [Docker](https://www.docker.com/community-edition), then startup Docker.

2. Clone the source, then execute `docker-compose` inside the directory.
   ``` sh
   $ git clone https://github.com/h404bi/wende
   $ cd wende/
   $ docker-compose up
   ```  

3. Waiting for image building, it will take some times, after building success, open your browser and enter `127.0.0.1:9191`, boom!

4. Play with it.

## License
Code: MIT. Copyright (c) 2016 by Chawye Hsu  
Data: [CC BY-NC-SA 4.0], except for the [ltp model] use its original license.  
这只是我的学士学位毕业设计项目（This is just the graduation project of my bachelor's degree）


[Anaconda]: https://www.continuum.io/downloads
[Microsoft Visual C++ Compiler for Python 2.7]: https://www.microsoft.com/en-us/download/details.aspx?id=44266
[pyltp]: https://github.com/HIT-SCIR/pyltp
[Git-Bash]: https://git-for-windows.github.io/
[原地址]: http://pan.baidu.com/share/link?shareid=1988562907&uk=2738088569
[百度云]: http://pan.baidu.com/s/1nv5ubJr
[CC BY-NC-SA 4.0]: https://creativecommons.org/licenses/by-nc-sa/4.0/
[ltp model]: https://github.com/HIT-SCIR/ltp#模型
