# Emacs Configuration

Personal [Doom Emacs](https://github.com/hlissner/doom-emacs) configuration files.
This is a literate configuration, and as such most of the information is in `config.org`.

Running `doom sync` will tangle `src` blocks in `config.org` to the actual configuration.
Doom's built-in package system is defined in `init.el`.


## Possible Additions

- [x] [`mu4e`](https://www.emacswiki.org/emacs/mu4e) for emails
  - [x] General setup
  - [x] Set an action to open a message in HTML
  - [x] Show unread email count in modeline
- [ ] Re-enable `format +onsave` with only specific formats enabled -- because
      enabling them makes exporting to html take too long and ruins `src` blocks
      with the formatting. 
- [x] Setting up an automatic daily planning system, with a generated daily 
      planning snippet or interactive command.
- [ ] Generate a new `org-super-agenda` view that takes displays the habits for
      other days if they are not a `Daily` tag.
