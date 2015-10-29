#Emacs
**insert a tab:** *ctrl-q tab*
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
