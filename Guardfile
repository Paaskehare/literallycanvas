#!/usr/bin/env python
from livereload.task import Task
from livereload.compiler import shell

Task.add('coffee/*.coffee', shell('make lib/js/literallycanvas.js'))
Task.add('scss/*.scss', shell('make scss'))