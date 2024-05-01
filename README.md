# Matrix99
Matrix99 - seq rand gen matrix for compilation perl

## Welcome 

### The following system is for our @COPY.
### Example script
```perl

TOPIC
Matrix99 cubic 1-100 sequencial DATA sigil runtimes;
MAIN MENU
===

! @ # $ % ^ & * ( !)
!! !@ !# !$ !% !^ !& !* !( @)
@! @@ @# @$ @% @^ @& @* @( #)
#! #@ ## #$ #% #^ #& #* #( $)
$! $@ $# $$ $% $^ $& $* $( %)
%! %@ %# %$ %% %^ %& %* %( ^)
^! ^@ ^# ^$ ^% ^^ ^& ^* ^( &)
&! &@ &# &$ &% &^ && &* &( *)
*! *@ *# *$ *% *^ *& ** *( ()
(! (@ (# ($ (% (^ (& (* (( !))

CTRL statements

$!='seq 0' <- #1
$@='seq 1'   #2
$#='seq 2'  #3
$$='seq 3' #4
$%='seq 4' #5
$^='seq 5' #6
$&='seq 6' #7  
$*='seq 7' #8 
$(='seq 8' #9

!! = repeat command
@@ = add id
## = ctrl comment
$$ = ctrl scalar 
%% = ctrl split
^^ = ctrl peek
&& = ctrl runtime
** = ctrl permission accessor 
(( = paren statement
)) = close statement paren

 +11
+22 +33 ... sum of 55))
+44 +55 ... sum of 99))
+66 +77 ... sum of 143))
+88 +99 ... sum of 187))

-11-------------------------!!
  -22------------------------@@
    -33------------------------##
      -44------------------------$$
        -55------------------------%%
          -66------------------------^^
            -77------------------------&&
              -88------------------------**
                -99------------------------((


```
TOPIC: This seems to be a header indicating the topic of the script, which appears to be about generating matrices in Perl.
MAIN MENU: This section seems to outline the main menu or structure of the script.
Control Statements: These are commands or directives used within the script to control its behavior. Here are the ones 

```perl
listed:
$!='seq 0': Assigns the sequence "seq 0" to the variable $!
$@='seq 1': Assigns the sequence "seq 1" to the variable $@
$#='seq 2': Assigns the sequence "seq 2" to the variable $#
$$='seq 3': Assigns the sequence "seq 3" to the variable $$
$%='seq 4': Assigns the sequence "seq 4" to the variable $%
$^='seq 5': Assigns the sequence "seq 5" to the variable $^
$&='seq 6': Assigns the sequence "seq 6" to the variable $&
$*='seq 7': Assigns the sequence "seq 7" to the variable $*
$(='seq 8': Assigns the sequence "seq 8" to the variable $(
```
Special Control Sequences: These sequences seem to have special meanings or actions within the script:
```
!!: Repeat command
@@: Add ID
##: Control comment
$$: Control scalar
%%: Control split
^^: Control peek
&&: Control runtime
**: Control permission accessor
((: Paren statement
)): Close statement paren
```

Matrix Generation: The script then seems to generate a matrix with certain patterns and sequences, including sums.
Explanation: The script generates a matrix with various sequences and control statements, likely for computational purposes or to demonstrate certain Perl functionalities.
