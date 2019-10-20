In my environment I had to:
unset PERL_MM_OPT

After compilation to remove everything except toolchain:
rm -rf build* dl uClibc* README* .git*
