# Monkberry Language

Atom/SublimeText support for Monkberry templates.

![Monkberry template in Atom](https://raw.githubusercontent.com/monkberry/language-monkberry/master/examples/screenshot.png)


## <kbd>Tab</kbd> triggers for
* `var` → `{{ $1 }}`
* `if` → `{% if $1 %} $2 {% endif %}`
* `else` → `{% else %}`
* `ife` → `{% if $1 %} $2 {% else %} $3 {% endif %}`
* `for` → `{% for $1 of $2 %} $3 {% endfor %}`
* `import` → `{% import "$1" %}`
* `unsafe` → `{% unsafe $1 %}`
* `block` → `{% block "$1" %} $2 {% endblock %}`


## Atom installation

1. Open Preferences → Install
2. Type `Monkberry` into the search field
3. Click the Install button


## Sublime Text installation

Get it through [Sublime Package Control](https://packagecontrol.io/).

If you haven't used it yet, just install it from the link above and then:

1. Press <kbd>Shift</kbd> + <kbd>Cmd</kbd> + <kbd>P</kbd> (OS X) or <kbd>Shift</kbd> + <kbd>Ctrl</kbd> + <kbd>P</kbd> (Windows)
2. Type `install`, to bring up the `Package Control: Install Package` option, and press Enter
3. Look for `Monkberry`, and press Enter to install it.
4. Choose `Monkberry` in the bottom right corner with one of your template files open (or in case you have inline templates use Handlebars instead of HTML, it's gracefully extending it so you shouldn't lose anything)
