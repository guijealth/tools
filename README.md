# tools
Tool specific configurations

## VSCode + Vim + Calva (Clojure)

./vscode

MAC: ALT -> OPTION

| Command            | Keybindings         |
| ------------------ | ------------------- |
| wrap around parens | `ALT + (` `ALT + )` |
| wrap around square | `ALT + [` `ALT + ]` |
| wrap around curly  | `ALT + {` `ALT + }` |
| wrap around quote  | `ALT + "`           |
| next or up sexp    | `L`                 |
| prev or up sexp    | `H`                 |
| slurp forward      | `>`                 |
| barf forward       | `<`                 |
| slurp backward     | `ALT + <`           |
| barf backward      | `ALT + >`           |
| kill sexp forward  | `ALT + d`           |
| raise sexp         | `ALT + SHIFT + r`   |
| drag sexp forward  | `ALT + j`           |
| drag sexp backward | `ALT + k`           |

| Command                   | Keybinding | Calva Command                       | CIDER Command                                      |
| ------------------------- | ---------- | ----------------------------------- | -------------------------------------------------- |
| open repl                 | SPC o r    | calva.showReplWindow                |                                                    |
| repl connect              | SPC m c    | calva.connect                       | cider-connect-clj                                  |
| send current form to repl | SPC m e E  | calva.sendCurrentFormToOutputWindow | cider-insert-last-sexp-in-repl                     |
| eval file                 | SPC m e b  | calva.loadFile                      | cider-eval-buffer                                  |
| eval top level form       | SPC m e d  | calva.evaluateCurrentTopLevelForm   | cider-eval-defun-at-point                          |
| eval current form         | SPC m e e  | calva.evaluateSelection             | cider-eval-last-sexp                               |
| eval selection            | SPC m e r  | visual: calva.evaluateSelection     | cider-eval-region                                  |
| eval to comment           | SPC m e c  | calva.evaluateSelectionAsComment    |                                                    |
| refresh all ns            | SPC m r r  | calva.refreshAll                    | cider-ns-refresh                                   |
| run ns tests              | SPC m t n  | calva.runNamespaceTests             | cider-test-run-ns-tests                            |
| run all tests             | SPC m t p  | calva.runAllTests                   | cider-test-run-project-tests                       |
| run current test          | SPC m t t  | calva.runTestUnderCursor            | cider-test-run-test                                |
|                           | SPC m ’    |                                     | cider-jack-in-clj                                  |
|                           | SPC m C    |                                     | cider-connect-cljs                                 |
|                           | SPC m M    |                                     | cider-macroexpand-all                              |
|                           | SPC m R    |                                     | hydra-cljr-help-menu/body                          |
|                           | SPC m e D  |                                     | cider-insert-defun-in-repl                         |
|                           | SPC m e R  |                                     | cider-insert-region-in-repl                        |
|                           | SPC m e u  |                                     | cider-undef                                        |
|                           | SPC m g b  |                                     | cider-pop-back                                     |
|                           | SPC m g g  |                                     | cider-find-var                                     |
|                           | SPC m g n  |                                     | cider-find-ns                                      |
|                           | SPC m h a  |                                     | cider-apropos                                      |
|                           | SPC m h c  |                                     | cider-clojuredocs                                  |
|                           | SPC m h d  |                                     | cider-doc                                          |
|                           | SPC m h j  |                                     | cider-javadoc                                      |
|                           | SPC m h n  |                                     | cider-find-ns                                      |
|                           | SPC m h w  |                                     | cider-clojuredocs-web                              |
|                           | SPC m i e  |                                     | cider-enlighten-mode                               |
|                           | SPC m i i  |                                     | cider-inspect                                      |
|                           | SPC m i r  |                                     | cider-inspect-last-result                          |
|                           | SPC m m “  |                                     | cider-jack-in-cljs                                 |
|                           | SPC m m    |                                     | cider-macroexpand-1                                |
|                           | SPC m n N  |                                     | cider-browse-ns-all                                |
|                           | SPC m n n  |                                     | cider-browse-ns                                    |
|                           | SPC m n r  |                                     | cider-ns-refresh                                   |
|                           | SPC m p d  |                                     | cider-pprint-eval-defun-at-point                   |
|                           | SPC m p D  |                                     | cider-pprint-eval-defun-to-comment                 |
|                           | SPC m p p  |                                     | cider-pprint-eval-last-sexp                        |
|                           | SPC m p P  |                                     | cider-pprint-eval-last-sexp-to-comment             |
|                           | SPC m p r  |                                     | cider-pprint-eval-last-sexp-to-repl                |
|                           | SPC m r B  |                                     | +clojure/cider-switch-to-repl-buffer-and-switch-ns |
|                           | SPC m r L  |                                     | cider-load-buffer-and-switch-to-repl-buffer        |
|                           | SPC m r R  |                                     | cider-restart                                      |
|                           | SPC m r b  |                                     | cider-switch-to-repl-buffer                        |
|                           | SPC m r c  |                                     | cider-find-and-clear-repl-output                   |
|                           | SPC m r l  |                                     | cider-load-buffer                                  |
|                           | SPC m r n  |                                     | cider-repl-set-ns                                  |
|                           | SPC m r q  |                                     | cider-quit                                         |
|                           | SPC m t a  |                                     | cider-test-rerun-test                              |
|                           | SPC m t l  |                                     | cider-test-run-loaded-tests                        |
|                           | SPC m t r  |                                     | cider-test-rerun-failed-tests                      |
|                           | SPC m t s  |                                     | cider-test-run-ns-tests-with-filters               |


