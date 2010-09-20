Add krl-mode.el to a directory on your load path and put the following lines in your .emacs file:

    ;;; KRL
    (require 'krl-mode)
    (add-to-list 'auto-mode-alist '("\.krl$" . krl-mode))
