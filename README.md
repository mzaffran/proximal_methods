# Proximal methods

_Authors : Mathieu Verchère and Margaux Zaffran_

## Setting

The following Julia packages are necessary in order to run the notebooks of this repository:
- JuMP
- OSQP
- PyPlot
- GZip
- CodecBzip2
- CPLEX (if not, you should modify in consequence ```cutting_plane_bundle_methods.ipynb```)

## References

```proximal_gradient.ipynb``` is an extended and completed version of this [notebook](https://perso.ensta-paris.fr/~pcarpent/SOD314/TPs/tp1.ipynb).

```cutting_plane_bundle_methods.ipynb```is an extended and completed version of this [notebook]
(https://perso.ensta-paris.fr/~pcarpent/SOD314/TPs/tp2.ipynb).

```diabetes``` comes from [this webpage](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/), and more precisely can be downloaded [here](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary/diabetes).

```libsvm_parser.jl``` has been downloaded from François Pacaud's [github](https://github.com/frapac), in the [LogisticOptTools folder](https://github.com/frapac/LogisticOptTools.jl/tree/master/src/io).
