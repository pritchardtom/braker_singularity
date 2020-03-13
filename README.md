# BRAKER Singularity Recipe

A Singularity recipe to install BRAKER (https://github.com/Gaius-Augustus/BRAKER)
and all its essential and optional dependencies.

## To-Do:

...

### Mandatory Deps:

- [ ] GeneMark-EX
- [ ] Augustus
- [ ] Bamtools
- [ ] DIAMOND

### Optional Deps:

- [ ] ProHint
- [ ] Samtools
- [ ] BioPython
- [ ] GenomeThreader
- [ ] Spaln
- [ ] Exonerate
- [ ] Tools from UCSC:
  - [ ] twoBitInfo
  - [ ] faToTwoBit
- [ ] MakeHub

### General:

- [ ] Check status of `cpanm POSIX` command.
- [ ] Check threads in Perl works okay.  Tests failed due to `locale` issues.

## Done:

Progress.

### Mandatory Deps:

- None.

### Optional Deps:

- [x] Python 3.6
- [x] cdbfasta

### General:

- [x] AUGUSTUS library dependencies installed.
- [x] GeneMark-ES dependencies installed.
