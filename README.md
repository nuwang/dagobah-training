# Intro to Galaxy Administration @ GCC2019

- [Join the Discussion](https://gitter.im/dagobah-training/Lobby)
- [Galaxy Training Materials](https://training.galaxyproject.org/)

## Location

'Greece' meeting room
Konzerthaus Freiburg

## Training VM instances

We are using 'small' instances from the [XSEDE JetStream](https://portal.xsede.org/jetstream) and [de.NBI](https://www.denbi.de/cloud) and NECTAR clouds with 2 cores, 4 GiB memory, 20 GiB disk, running a minimal Ubuntu 18.04 image

The instances have been bootstrapped with [a small Ansible playbook](/bootstrap-instances), which you may find useful for repeating the exercises at home using a VM, Docker image, etc.

## Timetable

### Monday
**1st July**

| **Time** | **Topic**                                | **Slides**                                             | **Exercises**                | **Instructor** |
| -------- | ---------                                | ---------                                              | -----------                  | -----------    |
| 10:00    | Welcome and introduction                 | [Welcome][welcome-slides]                              |                              | All            |
| 10:20    | Intro to Ansible                         | [Ansible][ansible-slides]                              | [Exercise][ansible-exercise] | S              |
| 11:00    | Galaxy Server Part 1: Basic Install      | [Database][db-slides], [uWSGI][uwsgi-slides]           | [Exercise][ansible-galaxy]   | M, N, H        |
| 12:00    | Lunch                                    |                                                        |                              |                |
| 13:00    | Galaxy Server Part 2: Towards Production | [NGINX][nginx-slides], [Supervisor][supervisor-slides] |                              | M, S, H        |
| 15:00    | Break (coffee & snacks)                  |                                                        |                              |                |
| 15:30    | Galaxy Server Part 3: Advanced Install   | [Production][production-slides]                        |                              | M, H           |
| 16:30    | Connecting Galaxy to a compute cluster   | [Slides][cluster-slides]                               | [Exercise][cluster-exercise] | N              |
| 17:30    | Close Day 1                              |                                                        |                              |                |

[welcome-slides]:      https://galaxyproject.github.io/dagobah-training/2019-gcc/00-intro/intro.html
[deployment-slides]:   https://training.galaxyproject.org/training-material/topics/admin/slides/introduction.html
[ansible-slides]:      https://training.galaxyproject.org/training-material/topics/admin/tutorials/ansible/slides.html
[ansible-exercise]:    https://training.galaxyproject.org/training-material/topics/admin/tutorials/ansible/tutorial.html#your-first-playbook-and-first-role
[db-slides]:           https://training.galaxyproject.org/training-material/topics/admin/tutorials/database/slides.html
[ansible-galaxy]:      https://training.galaxyproject.org/training-material/topics/admin/tutorials/ansible-galaxy/tutorial.html
[production-slides]:   https://training.galaxyproject.org/training-material/topics/admin/tutorials/production/slides.html
[nginx-slides]:        https://galaxyproject.github.io/dagobah-training/2019-gcc/03-production-basics/webservers.html#1
[uwsgi-slides]:        https://training.galaxyproject.org/training-material/topics/admin/tutorials/uwsgi/slides.html
[supervisor-slides]:   https://training.galaxyproject.org/training-material/topics/admin/tutorials/systemd-supervisor/slides.html
[cluster-slides]:      https://training.galaxyproject.org/training-material/topics/admin/tutorials/connect-to-compute-cluster/slides.html
[cluster-exercise]:    https://training.galaxyproject.org/training-material/topics/admin/tutorials/connect-to-compute-cluster/tutorial.html


### Instructors

* Simon Gladman - Galaxy Australia, Melbourne Bioinformatics, University of Melbourne, Australia
* Helena Rasche - Galaxy Europe (ELIXIR Galaxy WG, Elixir Germany, de.NBI), University of Freiburg, Germany
* Nate Coraor - Galaxy Project, Penn State University, USA
* John Chilton - Galaxy Project, Penn State University, USA
* Martin Čech - Galaxy Project, Penn State University, USA
* Enis Afgan
* Marius van den Beek
