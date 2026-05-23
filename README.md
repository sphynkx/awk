The True AWK (Aho/Kernighan/Weinberger 1988) written on Limbo. Intended to run on [Inferno64NG](https://github.com/sphynkx/inferno64ng) fork, but would be work on orig. and other forks also.

* All base functions and features of vanilla awk. 
* I/O adopted to Inferno arch.
* Local and independent math.

## Install
Place `module/awk.m` and `appl/cmd/awk.b` in system, modify `appl/cmd/mkfile` - add to `TARG` list:
```conf
	awk.dis\
```
Rebuild:
```bash
cd appl/cmd
mk install
```
