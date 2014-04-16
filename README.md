# DFS (JavaScript)

<img src="http://upload.wikimedia.org/wikipedia/commons/1/1f/Depth-first-tree.svg" alt="Depth First Search" align="right" height="140"/>

### [Depth First Search][dfs] implementation in JavaScript

This is part of a series of exercises to help me improve my understanding of programming languages and styles.<br/>
Implementation as described by [Prof. Erik Demaine][demaine] in a [recorded lecture][dfs-video] at MIT.<br/>
The graph constructed in the test is represented in the diagram shown on the right.

```bash
$ node test.js
1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12
```
If you have [Vagrant][vagrant] installed, you can build a simple dev environment. The repository will be mounted in `/srv`.
```bash
$ curl -O https://raw.github.com/adlawson/vagrantfiles/master/nodejs/Vagrantfile
$ vagrant up
$ vagrant ssh
```

<table>
    <thead>
        <tr>
            <th>Elixir</th>
            <th>Erlang</th>
            <th>JavaScript</th>
            <th>Julia</th>
            <th>Lua</th>
            <th>Python</th>
        </tr>
    <thead>
    <tbody>
        <tr>
            <td align="center"><a href="https://github.com/adlawson/dfs.ex">dfs.ex</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.erl">dfs.erl</a></td>
            <td align="center">dfs.js</td>
            <td align="center"><a href="https://github.com/adlawson/dfs.jl">dfs.jl</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.lua">dfs.lua</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.py">dfs.py</a></td>
        </tr>
        <tr>
            <td align="center"><a href="https://github.com/adlawson/bfs.ex">bfs.ex</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.erl">bfs.erl</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.js">bfs.js</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.jl">bfs.jl</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.lua">bfs.lua</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.py">bfs.py</a></td>
        </tr>
    </tbody>
</table>

```
The MIT License (MIT)

Copyright (c) 2014 Andrew Lawson <http://adlawson.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

[dfs]: http://en.wikipedia.org/wiki/Depth-first_search
[demaine]: http://en.wikipedia.org/wiki/Erik_Demaine
[dfs-video]: http://www.youtube.com/watch?v=AfSk24UTFS8
[vagrant]: http://vagrantup.com
