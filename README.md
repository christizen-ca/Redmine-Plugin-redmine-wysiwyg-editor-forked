# Redmine-Plugin-redmine-wysiwyg-editor-forked
Project for the plugin which is fixed some bugs in markdown snippets
It is forked from the plugin by taqueci/redmine_wysiwyg_editor (https://github.com/taqueci/redmine_wysiwyg_editor)

* Tested in Redmine 5.1.1 stable (Rails 6.1.7.6, Ruby 3.2.2-p53)
* Forked from the original author's version 0.34.0
* Fixed bugs while switching the editor and markdown snippets like footnote, search issues, search wiki, embeded codes like iframe, or mention
* Changed the logic not to use the visual editor for writing or editing comment (There are lots of conflicts about the AJAX actions, so I decided not to use the visual editor for that. However, still we can use the visual editor in writing issue or wiki page)

