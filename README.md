ubuntu
Last pushed: 2 days ago
•	Repo Info
•	Tags
Short Description
Ubuntu is a Debian-based Linux operating system based on free software.
Full Description
Supported tags and respectiveDockerfile links
•	12.04.5, 12.04, precise-20160108, precise (precise/Dockerfile)
•	14.04.3, 14.04, trusty-20160119, trusty, latest (trusty/Dockerfile)
•	15.04, vivid-20160122, vivid (vivid/Dockerfile)
•	15.10, wily-20160121, wily (wily/Dockerfile)
•	16.04, xenial-20160125, xenial (xenial/Dockerfile)
For more information about this image and its history, please see the relevant manifest file (library/ubuntu). This image is updated via pull requests to the docker-library/official-images GitHub repo.
For detailed information about the virtual/transfer sizes and individual layers of each of the above supported tags, please see the ubuntu/tag-details.md file in the docker-library/docs GitHub repo.
What is Ubuntu?
Ubuntu is a Debian-based Linux operating system, with Unity as its default desktop environment. It is based on free software and named after the Southern African philosophy of ubuntu (literally, "human-ness"), which often is translated as "humanity towards others" or "the belief in a universal bond of sharing that connects all humanity".
Development of Ubuntu is led by UK-based Canonical Ltd., a company owned by South African entrepreneur Mark Shuttleworth. Canonical generates revenue through the sale of technical support and other services related to Ubuntu. The Ubuntu project is publicly committed to the principles of open-source software development; people are encouraged to use free software, study how it works, improve upon it, and distribute it.
wikipedia.org/wiki/Ubuntu_(operating_system)
 
What's in this image?
/etc/apt/sources.list
ubuntu:14.04
$ docker run ubuntu:14.04 grep -v '^#' /etc/apt/sources.list

deb http://archive.ubuntu.com/ubuntu/ trusty main restricted
deb-src http://archive.ubuntu.com/ubuntu/ trusty main restricted

deb http://archive.ubuntu.com/ubuntu/ trusty-updates main restricted
deb-src http://archive.ubuntu.com/ubuntu/ trusty-updates main restricted

deb http://archive.ubuntu.com/ubuntu/ trusty universe
deb-src http://archive.ubuntu.com/ubuntu/ trusty universe
deb http://archive.ubuntu.com/ubuntu/ trusty-updates universe
deb-src http://archive.ubuntu.com/ubuntu/ trusty-updates universe


deb http://archive.ubuntu.com/ubuntu/ trusty-security main restricted
deb-src http://archive.ubuntu.com/ubuntu/ trusty-security main restricted
deb http://archive.ubuntu.com/ubuntu/ trusty-security universe
deb-src http://archive.ubuntu.com/ubuntu/ trusty-security universe
ubuntu:12.04
$ docker run ubuntu:12.04 cat /etc/apt/sources.list

deb http://archive.ubuntu.com/ubuntu/ precise main restricted
deb-src http://archive.ubuntu.com/ubuntu/ precise main restricted

deb http://archive.ubuntu.com/ubuntu/ precise-updates main restricted
deb-src http://archive.ubuntu.com/ubuntu/ precise-updates main restricted

deb http://archive.ubuntu.com/ubuntu/ precise universe
deb-src http://archive.ubuntu.com/ubuntu/ precise universe
deb http://archive.ubuntu.com/ubuntu/ precise-updates universe
deb-src http://archive.ubuntu.com/ubuntu/ precise-updates universe


deb http://archive.ubuntu.com/ubuntu/ precise-security main restricted
deb-src http://archive.ubuntu.com/ubuntu/ precise-security main restricted
deb http://archive.ubuntu.com/ubuntu/ precise-security universe
deb-src http://archive.ubuntu.com/ubuntu/ precise-security universe
Supported Docker versions
This image is officially supported on Docker version 1.9.1.
Support for older versions (down to 1.6) is provided on a best-effort basis.
Please see the Docker installation documentation for details on how to upgrade your Docker daemon.
User Feedback
Documentation
Documentation for this image is stored in the ubuntu/ directory of the docker-library/docs GitHub repo. Be sure to familiarize yourself with the repository's README.md file before attempting a pull request.
Issues
If you have any problems with or questions about this image, please contact us through a GitHub issue.
You can also reach many of the official image maintainers via the #docker-library IRC channel on Freenode.
Contributing
You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.
Before you start to code, we recommend discussing your plans through a GitHub issue, especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.

