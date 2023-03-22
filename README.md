EJ11
$ git clone https://github.com/adwinmbd/astro-blog-template

$ cd astro-blog-template


$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean


$ git init


EJ2
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

EJ3
$ git add .

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (main)
$ git log
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 17:25:58 2022 +0200

    feat: upgrade to astro v1.06

commit d3c2f283ae657af0a88df9225b5c6740ca5ee940
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 16:31:47 2022 +0200

    feat: add await to fetch calls.

commit 4d50b5cd3ad9991c1876c4c10d5f195c573599a0
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 16:14:04 2022 +0200

    feat: add post page.

commit 7f339eb94ff2117df827f2c03f7af0e35ec725a6
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Thu Mar 31 20:00:00 2022 +0300

:...skipping...
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 17:25:58 2022 +0200

    feat: upgrade to astro v1.06

commit d3c2f283ae657af0a88df9225b5c6740ca5ee940
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 16:31:47 2022 +0200

    feat: add await to fetch calls.

commit 4d50b5cd3ad9991c1876c4c10d5f195c573599a0
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 16:14:04 2022 +0200

    feat: add post page.

commit 7f339eb94ff2117df827f2c03f7af0e35ec725a6
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Thu Mar 31 20:00:00 2022 +0300

    feat:add contact page.

commit 62e0aa08a0e8e20cef3b2f80a9e6e8e7b06b2965
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Mon Feb 21 00:21:26 2022 +0100

    refractor: move tags page to the same level as home page.

commit c11bdcbce89e172980185902581f4c4b9cde5cd5
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Jan 2 19:58:40 2022 +0100

    feat: add favicon.

commit 606c6309ca240db5cc884600f9ad18ac9450b355
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Jan 2 10:01:48 2022 +0100

    feat: add styling to tags.

commit 12ef5ad8a98a16a9ad26adf8bc0a92740b535273
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Dec 19 12:16:21 2021 +0100

    feat: add markdown code styling.

commit 7eac45932a20f2c37feee48940d9915ce6a40445
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Dec 19 10:22:58 2021 +0100

    feat: add tagging functionality.

commit fa777df2d8b9139cb28e993aa5e8a9c20ec3e14a
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sat Dec 11 11:30:16 2021 +0100
...skipping...

                   SUMMARY OF LESS COMMANDS

      Commands marked with * may be preceded by a number, N.
      Notes in parentheses indicate the behavior if N is given.
      A key preceded by a caret indicates the Ctrl key; thus ^K is ctrl-K.

  h  H                 Display this help.
  q  :q  Q  :Q  ZZ     Exit.
 ---------------------------------------------------------------------------

                           MOVING

  e  ^E  j  ^N  CR  *  Forward  one line   (or N lines).
  y  ^Y  k  ^K  ^P  *  Backward one line   (or N lines).
  f  ^F  ^V  SPACE  *  Forward  one window (or N lines).
  b  ^B  ESC-v      *  Backward one window (or N lines).
  z                 *  Forward  one window (and set window to N).
  w                 *  Backward one window (and set window to N).
  ESC-SPACE         *  Forward  one window, but don't stop at end-of-file.
  d  ^D             *  Forward  one half-window (and set half-window to N).
  u  ^U             *  Backward one half-window (and set half-window to N).
  ESC-)  RightArrow *  Right one half screen width (or N positions).
  ESC-(  LeftArrow  *  Left  one half screen width (or N positions).
  ESC-}  ^RightArrow   Right to last column displayed.
  ESC-{  ^LeftArrow    Left  to first column.
  F                    Forward forever; like "tail -f".
  ESC-F                Like F but stop when search pattern is found.
  r  ^R  ^L            Repaint screen.
  R                    Repaint screen, discarding buffered input.
        ---------------------------------------------------
        Default "window" is the screen height.
        Default "half-window" is half of the screen height.
 ---------------------------------------------------------------------------

                          SEARCHING

  /pattern          *  Search forward for (N-th) matching line.
  ?pattern          *  Search backward for (N-th) matching line.
  n                 *  Repeat previous search (for N-th occurrence).
  N                 *  Repeat previous search in reverse direction.
  ESC-n             *  Repeat previous search, spanning files.
  ESC-N             *  Repeat previous search, reverse dir. & spanning files.
  ESC-u                Undo (toggle) search highlighting.
  ESC-U                Clear search highlighting.
  &pattern          *  Display only matching lines.
        ---------------------------------------------------
        A search pattern may begin with one or more of:
        ^N or !  Search for NON-matching lines.
        ^E or *  Search multiple files (pass thru END OF FILE).
        ^F or @  Start search at FIRST file (for /) or last file (for ?).
        ^K       Highlight matches, but don't move (KEEP position).
        ^R       Don't use REGULAR EXPRESSIONS.
        ^W       WRAP search if no match found.
 ---------------------------------------------------------------------------

                           JUMPING

HELP -- Press RETURN for more, or q when done...skipping...
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 17:25:58 2022 +0200

    feat: upgrade to astro v1.06

commit d3c2f283ae657af0a88df9225b5c6740ca5ee940
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 16:31:47 2022 +0200

    feat: add await to fetch calls.

commit 4d50b5cd3ad9991c1876c4c10d5f195c573599a0
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 16:14:04 2022 +0200

    feat: add post page.

commit 7f339eb94ff2117df827f2c03f7af0e35ec725a6
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Thu Mar 31 20:00:00 2022 +0300

    feat:add contact page.

commit 62e0aa08a0e8e20cef3b2f80a9e6e8e7b06b2965
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Mon Feb 21 00:21:26 2022 +0100

    refractor: move tags page to the same level as home page.

commit c11bdcbce89e172980185902581f4c4b9cde5cd5
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Jan 2 19:58:40 2022 +0100

    feat: add favicon.

commit 606c6309ca240db5cc884600f9ad18ac9450b355
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Jan 2 10:01:48 2022 +0100

    feat: add styling to tags.

commit 12ef5ad8a98a16a9ad26adf8bc0a92740b535273
Author: adwinmbd <adwin.mbidi@outlook.com>
Author: adwinmbd <adwin.mbidi@outlook.com>
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Dec 19 12:16:21 2021 +0100

    feat: add markdown code styling.

commit 7eac45932a20f2c37feee48940d9915ce6a40445
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Dec 19 10:22:58 2021 +0100

    feat: add tagging functionality.

commit fa777df2d8b9139cb28e993aa5e8a9c20ec3e14a
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sat Dec 11 11:30:16 2021 +0100

    refractor: delete unecessary files.

commit fee9ac4d2abbcc14ff15d436cb3ec7f03e6a233d
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sat Dec 11 10:57:27 2021 +0100

    refractor: updated projected description in README.

commit 6ae190873327c67faca9b9fadf239492d37392e1
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sat Dec 11 10:48:44 2021 +0100

    feat: add pagination.

commit 01e4b8286e1d4c093c972360e749667b83f69184
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Dec 5 19:30:52 2021 +0100

    feat: add tag list.

commit 06dd743e6d6c27aa663fe4265b66cc242998b3f8
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Nov 21 14:53:22 2021 +0100

    fix: patch posts not visible bug.

commit b2ba58491239e21d052d3c13f3d3f963c0bbe842
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Fri Nov 19 22:31:07 2021 +0100

    refractor: remove unecessary comments.

commit 6adef419da11877e6e7c96bee27b63788ded3994
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Fri Nov 19 21:56:20 2021 +0100

    feat: add initial source files.

commit 351bd9b9a3d0eda03c279d91a29008a69ed41ab7
Author: Adwin Mbidi <51711540+adwinmbd@users.noreply.github.com>
Date:   Fri Nov 19 21:53:33 2021 +0100

    Initial commit

EJ4
$ git branch
* main

EJ5 
$ git commit -m "Primer commit del examen"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (main)
$ $ git commit -m "Primer commit del examen"
bash: $: command not found



34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

EJ6
$ git log
commit 389bdf9447efe4b7c0795e3d098dd4a887cc360e (HEAD -> main, origin/main, origin/HEAD)
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 17:25:58 2022 +0200

    feat: upgrade to astro v1.06

commit d3c2f283ae657af0a88df9225b5c6740ca5ee940
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 16:31:47 2022 +0200

    feat: add await to fetch calls.

commit 4d50b5cd3ad9991c1876c4c10d5f195c573599a0
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Sun Aug 21 16:14:04 2022 +0200

    feat: add post page.

commit 7f339eb94ff2117df827f2c03f7af0e35ec725a6
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Thu Mar 31 20:00:00 2022 +0300

    feat:add contact page.

commit 62e0aa08a0e8e20cef3b2f80a9e6e8e7b06b2965
Author: Adwin Mbidi <adwin.mbidi@outlook.com>
Date:   Mon Feb 21 00:21:26 2022 +0100

    refractor: move tags page to the same level as home page.

commit c11bdcbce89e172980185902581f4c4b9cde5cd5
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Jan 2 19:58:40 2022 +0100

    feat: add favicon.

commit 606c6309ca240db5cc884600f9ad18ac9450b355
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Jan 2 10:01:48 2022 +0100

    feat: add styling to tags.

commit 12ef5ad8a98a16a9ad26adf8bc0a92740b535273
Author: adwinmbd <adwin.mbidi@outlook.com>
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Dec 19 12:16:21 2021 +0100

    feat: add markdown code styling.

commit 7eac45932a20f2c37feee48940d9915ce6a40445
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Dec 19 10:22:58 2021 +0100

    feat: add tagging functionality.

commit fa777df2d8b9139cb28e993aa5e8a9c20ec3e14a
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sat Dec 11 11:30:16 2021 +0100

    refractor: delete unecessary files.

commit fee9ac4d2abbcc14ff15d436cb3ec7f03e6a233d
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sat Dec 11 10:57:27 2021 +0100

    refractor: updated projected description in README.

commit 6ae190873327c67faca9b9fadf239492d37392e1
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sat Dec 11 10:48:44 2021 +0100

    feat: add pagination.

commit 01e4b8286e1d4c093c972360e749667b83f69184
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Dec 5 19:30:52 2021 +0100

    feat: add tag list.

commit 06dd743e6d6c27aa663fe4265b66cc242998b3f8
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Sun Nov 21 14:53:22 2021 +0100

    fix: patch posts not visible bug.

commit b2ba58491239e21d052d3c13f3d3f963c0bbe842
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Fri Nov 19 22:31:07 2021 +0100

    refractor: remove unecessary comments.

commit 6adef419da11877e6e7c96bee27b63788ded3994
Author: adwinmbd <adwin.mbidi@outlook.com>
Date:   Fri Nov 19 21:56:20 2021 +0100

    feat: add initial source files.

commit 351bd9b9a3d0eda03c279d91a29008a69ed41ab7
Author: Adwin Mbidi <51711540+adwinmbd@users.noreply.github.com>
Date:   Fri Nov 19 21:53:33 2021 +0100

    Initial commit

EJ7 Y EJ8
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

EJ9
$ git commit -am "Modificación del archivo readme.md"
[main c9fe633] Modificación del archivo readme.md
 1 file changed, 79 deletions(-)
EJ10

$ git commit -am "Salvador Vela Sanz"
[main 2b94d15] Salvador Vela Sanz
 1 file changed, 2 insertions(+)

EJ11
$ git branch
* main

EJ12 
$ git branch dev1

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (main)
$ git branch dev2


EJ13
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (main)
$ git checkout dev1
Switched to branch 'dev1'

EJ14
34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (dev1)
$ git checkout dev2
Switched to branch 'dev2'

34672@LAPTOP-KIVE1RPR MINGW64 ~/Desktop/Carpeta git/EJ2examen/astro-blog-template (dev2)
