[Cloned from **https://github.com/mfbx9da4/git-sub-dir** repository] (https://github.com/mfbx9da4/git-sub-dir)

##Usage
      

    python ggsb.py path/to/sub/dir <RECURSIVE>
    
<RECURSIVE> is a boolen `True` or `False`. Default is `True`.


##Example

Lets download the docs from twitter bootstrap https://github.com/twbs/bootstrap/tree/master/docs

    python ggsb.py twbs/bootstrap/docs

If we don't want it to be recursive

    python ggsb.py twbs/bootstrap/docs False
