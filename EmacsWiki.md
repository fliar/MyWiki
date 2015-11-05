#Emacs
**insert a tab:** *ctrl-q tab*<br>
**tab width**
~~~
(setq-default tab-width 4)
~~~
**set proxy:**
~~~
(setq url-proxy-services '(("http" . "111.111.111.111:11111")))
~~~
**melpa and gnu packages**
~~~
(setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                         ("melpa" . "http://melpa.org/packages/")))
~~~
**bind keys**
~~~
(global-set-key (kbd "<f12>") 'other-window)
~~~
**disable auto save**
~~~
(setq-default make-backup-files nil)
~~~
**package ops**
m-x list-packages<br>
mark i for install, d for delete<br>
x to execute
**return to shell**
~~~
c-z
~~~
*return emacs*
~~~
fg
~~~
~~~
%emacs
~~~
**enter set to newline + indent
~~~
(add-hook 'go-mode-hook '(lambda ()
  (local-set-key (kbd "RET") 'newline-and-indent)))
~~~