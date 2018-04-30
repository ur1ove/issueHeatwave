## Anaconda Prompt  
  
(base) C:\Windows\system32>conda update
~~~
CondaValueError: no package names supplied
# If you want to update to a newer version of Anaconda, type:
#
# $ conda update --prefix E:\Program\Anaconda3 anaconda
~~~
(base) C:\Windows\system32>conda update --prefix E:\Program\Anaconda3 anaconda
~~~
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.4.10
  latest version: 4.5.1

Please update conda by running

    $ conda update -n base conda



# All requested packages already installed.
~~~
(base) C:\Windows\system32>conda update -n base conda
~~~
Solving environment: done

## Package Plan ##

  environment location: E:\Program\Anaconda3

  added / updated specs:
    - conda


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    conda-4.5.1                |           py36_0         1.0 MB

The following packages will be UPDATED:

    conda: 4.4.10-py36_0 --> 4.5.1-py36_0

Proceed ([y]/n)? y


Downloading and Extracting Packages
conda 4.5.1: ########################################################## | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
~~~
(base) C:\Windows\system32>conda -V
~~~
conda 4.5.1
~~~
(base) C:\Windows\system32>python -V
~~~
Python 3.6.4 :: Anaconda custom (64-bit)
~~~
(base) C:\Windows\system32>conda install git
~~~
Solving environment: done

## Package Plan ##

  environment location: E:\Program\Anaconda3

  added / updated specs:
    - git


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    git-2.17.0                 |       hb9891f8_1        16.3 MB

The following NEW packages will be INSTALLED:

    git: 2.17.0-hb9891f8_1

Proceed ([y]/n)? y


Downloading and Extracting Packages
git 2.17.0############################################################# | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
~~~
(base) C:\Windows\system32>git
~~~
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch

   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
~~~
