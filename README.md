cl-todo
=======

Barebones command line ToDo list manager

cl-todo maintains a list of tasks in a user specified text file using
the widely used checklist formatting of Markdown. Tasks can be further
categorised in projects simply by adding tags with the `@` sign, e.g.
`@work`, `@personal`, `@home`, etc.

Inspiration
-----------

The idea of command line task / ToDo list manager is rather common (see
for instance, [TuDu](https://code.meskio.net/tudu/),
[Todo.txt](http://todotxt.org/), and
[Taskwarrior](https://taskwarrior.org/)). This particular project is,
however, mainly inspired from TaskWarrior. I tried using TaskWarrior
myself but I found it intimidating as I myself am not a poweruser in
terms of ToDo lists: I use them in phases, on a on-and-off basis. This
is why I felt psychologically bogged down by the horrible statistics
that show up when I want to use the _analytics_ features of TaskWarrior.
In the end, I decided that I needed something that was CLI-based but was
_not too smart_, something that did not offer to analyse my behaviour
and how good (or mostly bad) I was in managing my time and my tasks.

Thus began my own ToDo function in `.bashrc`, which I am now upgrading
to a small app called `cl-todo`.


Features
--------

Coming soon

Installation
------------

Copy the script `todo` to `/usr/local/bin` and make it user executable:
+ `$ sudo cp <path-to-script> /usr/local/bin`
+ `$ chmod u+x /usr/local/bin/todo`


Dependencies
------------

None

Example usage
-------------

Coming soon

To Do
-----

- [ ] Complete README
    - [ ] Add feature list
    - [ ] Add examples
- [ ] Add mobile synchronisation


LICENSE
-------

Copyright (C) 2020  Bedartha Goswami <bedartha@gmail.com>
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

