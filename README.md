### Translated HWMCC19 Benchmarks 

The original benchmark comes from the HWMCC19 website : http://fmv.jku.at/hwmcc19/

- `btor2` contains the original benchmarks in two tracks `BV` and `ABV`.
- `aig` contains only the `BV` track problems in AIGER format (there seems to be no way to have arrays in AIGER).
- `chc` contains the CHC format.
- `chcrel` is the rule dialect format supported by Z3.
- `vmt` is the VMT format problem translated from CHC using the Horn2VMT tool comes with IC3ia: https://es-static.fbk.eu/people/griggio/ic3ia/index.html

I obtained permission from Armin Biere for (1) creating derived works from the existing benchmarks and (2) putting them public available. However, I do not know what exactly the license is/has been applied on these, so please consult HWMCC19's organizors if you have questions about the license. Thanks!



