# abess

<details>

* Version: 0.2.0
* GitHub: https://github.com/abess-team/abess
* Source code: https://github.com/cran/abess
* Date/Publication: 2021-07-31 13:40:02 UTC
* Number of recursive dependencies: 48

Run `cloud_details(, "abess")` for more info

</details>

## In both

*   checking whether package ‘abess’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/abess/new/abess.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘abess’ ...
** package ‘abess’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I/usr/local/include  -fopenmp -DR_BUILD -I ../inst/include -fpic  -g -O2  -c Algorithm.cpp -o Algorithm.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I/usr/local/include  -fopenmp -DR_BUILD -I ../inst/include -fpic  -g -O2  -c Data.cpp -o Data.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/RcppEigenForward.h:30,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/RcppEigen.h:25,
...
../inst/include/Spectra/LinAlg/Arnoldi.h:205:40:   required from ‘void Spectra::Arnoldi<Scalar, ArnoldiOpType>::factorize_from(Spectra::Arnoldi<Scalar, ArnoldiOpType>::Index, Spectra::Arnoldi<Scalar, ArnoldiOpType>::Index, Spectra::Arnoldi<Scalar, ArnoldiOpType>::Index&) [with Scalar = double; ArnoldiOpType = Spectra::ArnoldiOp<double, Spectra::DenseSymMatProd<double>, Spectra::IdentityBOp>; Spectra::Arnoldi<Scalar, ArnoldiOpType>::Index = long int]’
../inst/include/Spectra/LinAlg/Arnoldi.h:146:18:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:650:34: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
  650 |   return internal::first_aligned<int(unpacket_traits<DefaultPacketType>::alignment),Derived>(m);
      |                                  ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:181: abess.o] Error 1
ERROR: compilation failed for package ‘abess’
* removing ‘/tmp/workdir/abess/new/abess.Rcheck/abess’


```
### CRAN

```
* installing *source* package ‘abess’ ...
** package ‘abess’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I/usr/local/include  -fopenmp -DR_BUILD -I ../inst/include -fpic  -g -O2  -c Algorithm.cpp -o Algorithm.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I/usr/local/include  -fopenmp -DR_BUILD -I ../inst/include -fpic  -g -O2  -c Data.cpp -o Data.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/RcppEigenForward.h:30,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/RcppEigen.h:25,
...
../inst/include/Spectra/LinAlg/Arnoldi.h:205:40:   required from ‘void Spectra::Arnoldi<Scalar, ArnoldiOpType>::factorize_from(Spectra::Arnoldi<Scalar, ArnoldiOpType>::Index, Spectra::Arnoldi<Scalar, ArnoldiOpType>::Index, Spectra::Arnoldi<Scalar, ArnoldiOpType>::Index&) [with Scalar = double; ArnoldiOpType = Spectra::ArnoldiOp<double, Spectra::DenseSymMatProd<double>, Spectra::IdentityBOp>; Spectra::Arnoldi<Scalar, ArnoldiOpType>::Index = long int]’
../inst/include/Spectra/LinAlg/Arnoldi.h:146:18:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:650:34: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
  650 |   return internal::first_aligned<int(unpacket_traits<DefaultPacketType>::alignment),Derived>(m);
      |                                  ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:181: abess.o] Error 1
ERROR: compilation failed for package ‘abess’
* removing ‘/tmp/workdir/abess/old/abess.Rcheck/abess’


```
# ActivePathways

<details>

* Version: 1.0.2
* GitHub: https://github.com/reimandlab/ActivePathways
* Source code: https://github.com/cran/ActivePathways
* Date/Publication: 2020-07-09 17:20:02 UTC
* Number of recursive dependencies: 88

Run `cloud_details(, "ActivePathways")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/ActivePathways/new/ActivePathways.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘ActivePathways/DESCRIPTION’ ... OK
* this is package ‘ActivePathways’ version ‘1.0.2’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
  [ FAIL 1 | WARN 0 | SKIP 0 | PASS 70 ]
  Error: Test failures
  Execution halted
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘ActivePathways-vignette.Rmd’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 1 ERROR, 1 NOTE





```
### CRAN

```
* using log directory ‘/tmp/workdir/ActivePathways/old/ActivePathways.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘ActivePathways/DESCRIPTION’ ... OK
* this is package ‘ActivePathways’ version ‘1.0.2’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
  [ FAIL 1 | WARN 0 | SKIP 0 | PASS 70 ]
  Error: Test failures
  Execution halted
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘ActivePathways-vignette.Rmd’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 1 ERROR, 1 NOTE





```
# apisensr

<details>

* Version: 0.3.0
* GitHub: https://github.com/dhaine/apisensr
* Source code: https://github.com/cran/apisensr
* Date/Publication: 2021-03-15 11:20:09 UTC
* Number of recursive dependencies: 127

Run `cloud_details(, "apisensr")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/apisensr/new/apisensr.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘apisensr/DESCRIPTION’ ... OK
* this is package ‘apisensr’ version ‘0.3.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘episensr’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/apisensr/old/apisensr.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘apisensr/DESCRIPTION’ ... OK
* this is package ‘apisensr’ version ‘0.3.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘episensr’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# backShift

<details>

* Version: 0.1.4.3
* GitHub: https://github.com/christinaheinze/backShift
* Source code: https://github.com/cran/backShift
* Date/Publication: 2020-05-06 11:30:03 UTC
* Number of recursive dependencies: 89

Run `cloud_details(, "backShift")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/backShift/new/backShift.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘backShift/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘backShift’ version ‘0.1.4.3’
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘exampleBackShift.Rmd’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 2 NOTEs





```
### CRAN

```
* using log directory ‘/tmp/workdir/backShift/old/backShift.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘backShift/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘backShift’ version ‘0.1.4.3’
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘exampleBackShift.Rmd’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 2 NOTEs





```
# bayesdfa

<details>

* Version: 1.1.0
* GitHub: https://github.com/fate-ewi/bayesdfa
* Source code: https://github.com/cran/bayesdfa
* Date/Publication: 2021-05-28 18:10:05 UTC
* Number of recursive dependencies: 81

Run `cloud_details(, "bayesdfa")` for more info

</details>

## In both

*   checking whether package ‘bayesdfa’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/bayesdfa/new/bayesdfa.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘bayesdfa’ ...
** package ‘bayesdfa’ successfully unpacked and MD5 sums checked
** using staged installation
** libs


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -D_REENTRANT -DSTAN_THREADS   -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/RcppEigenForward.h:30,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/ProductEvaluators.h:35:90:   required from ‘Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::evaluator(const XprType&) [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Options = 0; Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::XprType = Eigen::Product<Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>, Eigen::Matrix<double, -1, 1>, 0>]’
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_dfa_namespace::model_dfa; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stanExports_dfa.o] Error 1
ERROR: compilation failed for package ‘bayesdfa’
* removing ‘/tmp/workdir/bayesdfa/new/bayesdfa.Rcheck/bayesdfa’


```
### CRAN

```
* installing *source* package ‘bayesdfa’ ...
** package ‘bayesdfa’ successfully unpacked and MD5 sums checked
** using staged installation
** libs


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -D_REENTRANT -DSTAN_THREADS   -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/RcppEigenForward.h:30,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/ProductEvaluators.h:35:90:   required from ‘Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::evaluator(const XprType&) [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Options = 0; Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::XprType = Eigen::Product<Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>, Eigen::Matrix<double, -1, 1>, 0>]’
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_dfa_namespace::model_dfa; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stanExports_dfa.o] Error 1
ERROR: compilation failed for package ‘bayesdfa’
* removing ‘/tmp/workdir/bayesdfa/old/bayesdfa.Rcheck/bayesdfa’


```
# bayesGAM

<details>

* Version: 0.0.1
* GitHub: NA
* Source code: https://github.com/cran/bayesGAM
* Date/Publication: 2020-11-18 10:20:06 UTC
* Number of recursive dependencies: 84

Run `cloud_details(, "bayesGAM")` for more info

</details>

## In both

*   checking whether package ‘bayesGAM’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/bayesGAM/new/bayesGAM.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘bayesGAM’ ...
** package ‘bayesGAM’ successfully unpacked and MD5 sums checked
** using staged installation
** libs


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -D_REENTRANT -DSTAN_THREADS   -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/RcppEigenForward.h:30,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/ProductEvaluators.h:35:90:   required from ‘Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::evaluator(const XprType&) [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Options = 0; Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::XprType = Eigen::Product<Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>, Eigen::Matrix<double, -1, 1>, 0>]’
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_glmm_discrete_namespace::model_glmm_discrete; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stanExports_glmm_discrete.o] Error 1
ERROR: compilation failed for package ‘bayesGAM’
* removing ‘/tmp/workdir/bayesGAM/new/bayesGAM.Rcheck/bayesGAM’


```
### CRAN

```
* installing *source* package ‘bayesGAM’ ...
** package ‘bayesGAM’ successfully unpacked and MD5 sums checked
** using staged installation
** libs


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -D_REENTRANT -DSTAN_THREADS   -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/RcppEigenForward.h:30,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/ProductEvaluators.h:35:90:   required from ‘Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::evaluator(const XprType&) [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Options = 0; Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::XprType = Eigen::Product<Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>, Eigen::Matrix<double, -1, 1>, 0>]’
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_multresponse_continuous_namespace::model_multresponse_continuous; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stanExports_multresponse_continuous.o] Error 1
ERROR: compilation failed for package ‘bayesGAM’
* removing ‘/tmp/workdir/bayesGAM/old/bayesGAM.Rcheck/bayesGAM’


```
# Boom

<details>

* Version: 0.9.7
* GitHub: NA
* Source code: https://github.com/cran/Boom
* Date/Publication: 2021-02-23 17:40:03 UTC
* Number of recursive dependencies: 32

Run `cloud_details(, "Boom")` for more info

</details>

## In both

*   checking whether package ‘Boom’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/Boom/new/Boom.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘Boom’ ...
** package ‘Boom’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c boom_r_tools.cpp -o boom_r_tools.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c create_point_process.cpp -o create_point_process.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c create_mixture_component.cpp -o create_mixture_component.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c parse_model_formula.cpp -o parse_model_formula.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c extract_mixture_data.cpp -o extract_mixture_data.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c seed_rng_from_R.cpp -o seed_rng_from_R.o
...
../inst/include/Eigen/src/Core/products/TriangularMatrixVector.h:282:27:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
../inst/include/Eigen/src/Householder/BlockHouseholder.h:85:55:   required from ‘void Eigen::internal::apply_block_householder_on_the_left(MatrixType&, const VectorsType&, const CoeffsType&, bool) [with MatrixType = Eigen::Block<Eigen::Matrix<double, -1, -1>, -1, -1, false>; VectorsType = Eigen::Block<Eigen::Matrix<double, -1, -1>, -1, -1, false>; CoeffsType = Eigen::VectorBlock<const Eigen::Matrix<double, -1, 1>, -1>]’
../inst/include/Eigen/src/Householder/HouseholderSequence.h:333:46:   required from ‘void Eigen::HouseholderSequence<VectorsType, CoeffsType, Side>::applyThisOnTheLeft(Dest&, Workspace&) const [with Dest = Eigen::Matrix<double, -1, -1>; Workspace = Eigen::Matrix<double, 1, -1>; VectorsType = Eigen::Matrix<double, -1, -1>; CoeffsType = Eigen::Matrix<double, -1, 1>; int Side = 1]’
../inst/include/Eigen/src/SVD/JacobiSVD.h:237:9:   required from ‘bool Eigen::internal::qr_preconditioner_impl<MatrixType, 2, 0, true>::run(Eigen::JacobiSVD<MatrixType, 2>&, const MatrixType&) [with MatrixType = Eigen::Matrix<double, -1, -1>]’
../inst/include/Eigen/src/SVD/JacobiSVD.h:684:5:   required from ‘Eigen::JacobiSVD<MatrixType, QRPreconditioner>& Eigen::JacobiSVD<MatrixType, QRPreconditioner>::compute(const MatrixType&, unsigned int) [with _MatrixType = Eigen::Matrix<double, -1, -1>; int QRPreconditioner = 2; Eigen::JacobiSVD<MatrixType, QRPreconditioner>::MatrixType = Eigen::Matrix<double, -1, -1>]’
../inst/include/Eigen/src/SVD/JacobiSVD.h:548:7:   required from ‘Eigen::JacobiSVD<MatrixType, QRPreconditioner>::JacobiSVD(const MatrixType&, unsigned int) [with _MatrixType = Eigen::Matrix<double, -1, -1>; int QRPreconditioner = 2; Eigen::JacobiSVD<MatrixType, QRPreconditioner>::MatrixType = Eigen::Matrix<double, -1, -1>]’
LinAlg/Matrix.cpp:759:67:   required from here
../inst/include/Eigen/src/Core/CoreEvaluators.h:960:8: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
ERROR: compilation failed for package ‘Boom’
* removing ‘/tmp/workdir/Boom/new/Boom.Rcheck/Boom’


```
### CRAN

```
* installing *source* package ‘Boom’ ...
** package ‘Boom’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c boom_r_tools.cpp -o boom_r_tools.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c create_point_process.cpp -o create_point_process.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c create_mixture_component.cpp -o create_mixture_component.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c parse_model_formula.cpp -o parse_model_formula.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c extract_mixture_data.cpp -o extract_mixture_data.o
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I. -I../inst/include -IBmath -Imath/cephes -DADD_ -DR_NO_REMAP -DEIGEN_WARNINGS_DISABLED  -I/usr/local/include   -fpic  -g -O2  -c seed_rng_from_R.cpp -o seed_rng_from_R.o
...
../inst/include/Eigen/src/Core/products/TriangularMatrixVector.h:282:27:   [ skipping 14 instantiation contexts, use -ftemplate-backtrace-limit=0 to disable ]
../inst/include/Eigen/src/Householder/BlockHouseholder.h:85:55:   required from ‘void Eigen::internal::apply_block_householder_on_the_left(MatrixType&, const VectorsType&, const CoeffsType&, bool) [with MatrixType = Eigen::Block<Eigen::Matrix<double, -1, -1>, -1, -1, false>; VectorsType = Eigen::Block<Eigen::Matrix<double, -1, -1>, -1, -1, false>; CoeffsType = Eigen::VectorBlock<const Eigen::Matrix<double, -1, 1>, -1>]’
../inst/include/Eigen/src/Householder/HouseholderSequence.h:333:46:   required from ‘void Eigen::HouseholderSequence<VectorsType, CoeffsType, Side>::applyThisOnTheLeft(Dest&, Workspace&) const [with Dest = Eigen::Matrix<double, -1, -1>; Workspace = Eigen::Matrix<double, 1, -1>; VectorsType = Eigen::Matrix<double, -1, -1>; CoeffsType = Eigen::Matrix<double, -1, 1>; int Side = 1]’
../inst/include/Eigen/src/SVD/JacobiSVD.h:237:9:   required from ‘bool Eigen::internal::qr_preconditioner_impl<MatrixType, 2, 0, true>::run(Eigen::JacobiSVD<MatrixType, 2>&, const MatrixType&) [with MatrixType = Eigen::Matrix<double, -1, -1>]’
../inst/include/Eigen/src/SVD/JacobiSVD.h:684:5:   required from ‘Eigen::JacobiSVD<MatrixType, QRPreconditioner>& Eigen::JacobiSVD<MatrixType, QRPreconditioner>::compute(const MatrixType&, unsigned int) [with _MatrixType = Eigen::Matrix<double, -1, -1>; int QRPreconditioner = 2; Eigen::JacobiSVD<MatrixType, QRPreconditioner>::MatrixType = Eigen::Matrix<double, -1, -1>]’
../inst/include/Eigen/src/SVD/JacobiSVD.h:548:7:   required from ‘Eigen::JacobiSVD<MatrixType, QRPreconditioner>::JacobiSVD(const MatrixType&, unsigned int) [with _MatrixType = Eigen::Matrix<double, -1, -1>; int QRPreconditioner = 2; Eigen::JacobiSVD<MatrixType, QRPreconditioner>::MatrixType = Eigen::Matrix<double, -1, -1>]’
LinAlg/Matrix.cpp:759:67:   required from here
../inst/include/Eigen/src/Core/CoreEvaluators.h:960:8: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
ERROR: compilation failed for package ‘Boom’
* removing ‘/tmp/workdir/Boom/old/Boom.Rcheck/Boom’


```
# bsts

<details>

* Version: 0.9.7
* GitHub: NA
* Source code: https://github.com/cran/bsts
* Date/Publication: 2021-07-02 04:30:07 UTC
* Number of recursive dependencies: 37

Run `cloud_details(, "bsts")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/bsts/new/bsts.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘bsts/DESCRIPTION’ ... OK
* this is package ‘bsts’ version ‘0.9.7’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'BoomSpikeSlab', 'Boom'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/bsts/old/bsts.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘bsts/DESCRIPTION’ ... OK
* this is package ‘bsts’ version ‘0.9.7’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'BoomSpikeSlab', 'Boom'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# CausalImpact

<details>

* Version: 1.2.7
* GitHub: NA
* Source code: https://github.com/cran/CausalImpact
* Date/Publication: 2021-06-07 06:40:02 UTC
* Number of recursive dependencies: 68

Run `cloud_details(, "CausalImpact")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/CausalImpact/new/CausalImpact.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘CausalImpact/DESCRIPTION’ ... OK
* this is package ‘CausalImpact’ version ‘1.2.7’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'bsts', 'Boom'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/CausalImpact/old/CausalImpact.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘CausalImpact/DESCRIPTION’ ... OK
* this is package ‘CausalImpact’ version ‘1.2.7’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'bsts', 'Boom'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# CB2

<details>

* Version: 1.3.4
* GitHub: NA
* Source code: https://github.com/cran/CB2
* Date/Publication: 2020-07-24 09:42:24 UTC
* Number of recursive dependencies: 105

Run `cloud_details(, "CB2")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/CB2/new/CB2.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘CB2/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘CB2’ version ‘1.3.4’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘metap’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/CB2/old/CB2.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘CB2/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘CB2’ version ‘1.3.4’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘metap’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# cbar

<details>

* Version: 0.1.3
* GitHub: https://github.com/zedoul/cbar
* Source code: https://github.com/cran/cbar
* Date/Publication: 2017-10-24 13:20:22 UTC
* Number of recursive dependencies: 63

Run `cloud_details(, "cbar")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/cbar/new/cbar.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘cbar/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘cbar’ version ‘0.1.3’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'Boom', 'bsts'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/cbar/old/cbar.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘cbar/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘cbar’ version ‘0.1.3’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'Boom', 'bsts'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# CompareCausalNetworks

<details>

* Version: 0.2.6.2
* GitHub: https://github.com/christinaheinze/CompareCausalNetworks
* Source code: https://github.com/cran/CompareCausalNetworks
* Date/Publication: 2020-02-17 19:00:42 UTC
* Number of recursive dependencies: 98

Run `cloud_details(, "CompareCausalNetworks")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/CompareCausalNetworks/new/CompareCausalNetworks.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘CompareCausalNetworks/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘CompareCausalNetworks’ version ‘0.2.6.2’
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
* checking for unstated dependencies in examples ... OK
* checking contents of ‘data’ directory ... OK
* checking data for non-ASCII characters ... OK
* checking data for ASCII and uncompressed saves ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* DONE
Status: 1 NOTE





```
### CRAN

```
* using log directory ‘/tmp/workdir/CompareCausalNetworks/old/CompareCausalNetworks.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘CompareCausalNetworks/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘CompareCausalNetworks’ version ‘0.2.6.2’
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
* checking for unstated dependencies in examples ... OK
* checking contents of ‘data’ directory ... OK
* checking data for non-ASCII characters ... OK
* checking data for ASCII and uncompressed saves ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* DONE
Status: 1 NOTE





```
# diceR

<details>

* Version: 1.1.0
* GitHub: https://github.com/AlineTalhouk/diceR
* Source code: https://github.com/cran/diceR
* Date/Publication: 2021-07-23 19:30:01 UTC
* Number of recursive dependencies: 152

Run `cloud_details(, "diceR")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/diceR/new/diceR.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘diceR/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘diceR’ version ‘1.1.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘NMF’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/diceR/old/diceR.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘diceR/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘diceR’ version ‘1.1.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘NMF’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# dimRed

<details>

* Version: 0.2.3
* GitHub: https://github.com/gdkrmr/dimRed
* Source code: https://github.com/cran/dimRed
* Date/Publication: 2019-05-08 08:10:07 UTC
* Number of recursive dependencies: 128

Run `cloud_details(, "dimRed")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/dimRed/new/dimRed.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘dimRed/DESCRIPTION’ ... OK
* this is package ‘dimRed’ version ‘0.2.3’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
  
  Error: Test failures
  Execution halted
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘dimensionality-reduction.Rnw’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 2 ERRORs, 2 NOTEs





```
### CRAN

```
* using log directory ‘/tmp/workdir/dimRed/old/dimRed.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘dimRed/DESCRIPTION’ ... OK
* this is package ‘dimRed’ version ‘0.2.3’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
  
  Error: Test failures
  Execution halted
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘dimensionality-reduction.Rnw’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 2 ERRORs, 2 NOTEs





```
# eff2

<details>

* Version: 1.0.0
* GitHub: https://github.com/richardkwo/eff2
* Source code: https://github.com/cran/eff2
* Date/Publication: 2021-05-21 08:10:05 UTC
* Number of recursive dependencies: 112

Run `cloud_details(, "eff2")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/eff2/new/eff2.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘eff2/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘eff2’ version ‘1.0.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'pcalg', 'RBGL'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/eff2/old/eff2.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘eff2/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘eff2’ version ‘1.0.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'pcalg', 'RBGL'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# fabisearch

<details>

* Version: 0.0.2.4
* GitHub: https://github.com/mondrus96/FaBiSearch
* Source code: https://github.com/cran/fabisearch
* Date/Publication: 2021-02-24 09:40:05 UTC
* Number of recursive dependencies: 78

Run `cloud_details(, "fabisearch")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/fabisearch/new/fabisearch.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘fabisearch/DESCRIPTION’ ... OK
* this is package ‘fabisearch’ version ‘0.0.2.4’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘NMF’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/fabisearch/old/fabisearch.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘fabisearch/DESCRIPTION’ ... OK
* this is package ‘fabisearch’ version ‘0.0.2.4’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘NMF’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# fdaPDE

<details>

* Version: 1.0-9
* GitHub: NA
* Source code: https://github.com/cran/fdaPDE
* Date/Publication: 2020-05-15 15:10:02 UTC
* Number of recursive dependencies: 59

Run `cloud_details(, "fdaPDE")` for more info

</details>

## In both

*   checking whether package ‘fdaPDE’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/fdaPDE/new/fdaPDE.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘fdaPDE’ ...
** package ‘fdaPDE’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I/usr/local/include   -fpic  -g -O2  -c FEMeval.cpp -o FEMeval.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/StdVector:14,
                 from fdaPDE.h:27,
                 from FEMeval.cpp:11:
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/arch/SSE/PacketMath.h:60:39: warning: ignoring attributes on template argument ‘__m128’ {aka ‘__vector(4) float’} [-Wignored-attributes]
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/SVD/BDCSVD.h:137:5:   required from ‘Eigen::BDCSVD<MatrixType>::BDCSVD(const MatrixType&, unsigned int) [with _MatrixType = Eigen::Matrix<double, -1, -1>; Eigen::BDCSVD<MatrixType>::MatrixType = Eigen::Matrix<double, -1, -1>]’
mixedFEFPCA_imp.h:241:26:   required from ‘void MixedFEFPCABase<Integrator, ORDER, mydim, ndim>::computeCumulativePercentageExplained() [with Integrator = IntegratorTetrahedronP2; int ORDER = 1; int mydim = 3; int ndim = 3]’
mixedFEFPCA_imp.h:373:87:   required from ‘void MixedFEFPCA<Integrator, ORDER, mydim, ndim>::apply() [with Integrator = IntegratorTetrahedronP2; int ORDER = 1; int mydim = 3; int ndim = 3]’
mixedFEFPCA_imp.h:344:6:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/CoreEvaluators.h:960:8: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:181: fdaPDE.o] Error 1
ERROR: compilation failed for package ‘fdaPDE’
* removing ‘/tmp/workdir/fdaPDE/new/fdaPDE.Rcheck/fdaPDE’


```
### CRAN

```
* installing *source* package ‘fdaPDE’ ...
** package ‘fdaPDE’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I/usr/local/include   -fpic  -g -O2  -c FEMeval.cpp -o FEMeval.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/StdVector:14,
                 from fdaPDE.h:27,
                 from FEMeval.cpp:11:
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/arch/SSE/PacketMath.h:60:39: warning: ignoring attributes on template argument ‘__m128’ {aka ‘__vector(4) float’} [-Wignored-attributes]
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/SVD/BDCSVD.h:137:5:   required from ‘Eigen::BDCSVD<MatrixType>::BDCSVD(const MatrixType&, unsigned int) [with _MatrixType = Eigen::Matrix<double, -1, -1>; Eigen::BDCSVD<MatrixType>::MatrixType = Eigen::Matrix<double, -1, -1>]’
mixedFEFPCA_imp.h:241:26:   required from ‘void MixedFEFPCABase<Integrator, ORDER, mydim, ndim>::computeCumulativePercentageExplained() [with Integrator = IntegratorTetrahedronP2; int ORDER = 1; int mydim = 3; int ndim = 3]’
mixedFEFPCA_imp.h:373:87:   required from ‘void MixedFEFPCA<Integrator, ORDER, mydim, ndim>::apply() [with Integrator = IntegratorTetrahedronP2; int ORDER = 1; int mydim = 3; int ndim = 3]’
mixedFEFPCA_imp.h:344:6:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/CoreEvaluators.h:960:8: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:181: fdaPDE.o] Error 1
ERROR: compilation failed for package ‘fdaPDE’
* removing ‘/tmp/workdir/fdaPDE/old/fdaPDE.Rcheck/fdaPDE’


```
# gllvm

<details>

* Version: 1.3.1
* GitHub: https://github.com/JenniNiku/gllvm
* Source code: https://github.com/cran/gllvm
* Date/Publication: 2021-07-28 17:20:02 UTC
* Number of recursive dependencies: 59

Run `cloud_details(, "gllvm")` for more info

</details>

## In both

*   checking whether package ‘gllvm’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/gllvm/new/gllvm.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘gllvm’ ...
** package ‘gllvm’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/TMB/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I/usr/local/include   -fpic  -g -O2  -c gllvm.cpp -o gllvm.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/TMB/include/TMB.hpp:53,
                 from gllvm.cpp:2:
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/arch/SSE/PacketMath.h:60:39: warning: ignoring attributes on template argument ‘__m128’ {aka ‘__vector(4) float’} [-Wignored-attributes]
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Assign.h:66:28:   required from ‘Derived& Eigen::MatrixBase<Derived>::operator=(const Eigen::DenseBase<OtherDerived>&) [with OtherDerived = Eigen::Product<Eigen::Map<const Eigen::Matrix<double, -1, -1>, 0, Eigen::Stride<0, 0> >, Eigen::Map<const Eigen::Matrix<double, -1, -1>, 0, Eigen::Stride<0, 0> >, 0>; Derived = Eigen::Map<Eigen::Matrix<double, -1, -1>, 0, Eigen::Stride<0, 0> >]’
/opt/R/4.0.3/lib/R/site-library/TMB/include/atomic_math.hpp:426:1:   required from ‘void atomic::matmul(const CppAD::vector<Type>&, CppAD::vector<Type>&) [with Double = double]’
/opt/R/4.0.3/lib/R/site-library/TMB/include/atomic_math.hpp:426:1:   required from ‘bool atomic::atomicmatmul<Type>::forward(size_t, size_t, const CppAD::vector<bool>&, CppAD::vector<bool>&, const CppAD::vector<Type>&, CppAD::vector<Type>&) [with Type = double; size_t = long unsigned int]’
/opt/R/4.0.3/lib/R/site-library/TMB/include/atomic_math.hpp:426:1:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/CoreEvaluators.h:960:8: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:181: gllvm.o] Error 1
ERROR: compilation failed for package ‘gllvm’
* removing ‘/tmp/workdir/gllvm/new/gllvm.Rcheck/gllvm’


```
### CRAN

```
* installing *source* package ‘gllvm’ ...
** package ‘gllvm’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/TMB/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I/usr/local/include   -fpic  -g -O2  -c gllvm.cpp -o gllvm.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/TMB/include/TMB.hpp:53,
                 from gllvm.cpp:2:
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/arch/SSE/PacketMath.h:60:39: warning: ignoring attributes on template argument ‘__m128’ {aka ‘__vector(4) float’} [-Wignored-attributes]
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Assign.h:66:28:   required from ‘Derived& Eigen::MatrixBase<Derived>::operator=(const Eigen::DenseBase<OtherDerived>&) [with OtherDerived = Eigen::Product<Eigen::Map<const Eigen::Matrix<double, -1, -1>, 0, Eigen::Stride<0, 0> >, Eigen::Map<const Eigen::Matrix<double, -1, -1>, 0, Eigen::Stride<0, 0> >, 0>; Derived = Eigen::Map<Eigen::Matrix<double, -1, -1>, 0, Eigen::Stride<0, 0> >]’
/opt/R/4.0.3/lib/R/site-library/TMB/include/atomic_math.hpp:426:1:   required from ‘void atomic::matmul(const CppAD::vector<Type>&, CppAD::vector<Type>&) [with Double = double]’
/opt/R/4.0.3/lib/R/site-library/TMB/include/atomic_math.hpp:426:1:   required from ‘bool atomic::atomicmatmul<Type>::forward(size_t, size_t, const CppAD::vector<bool>&, CppAD::vector<bool>&, const CppAD::vector<Type>&, CppAD::vector<Type>&) [with Type = double; size_t = long unsigned int]’
/opt/R/4.0.3/lib/R/site-library/TMB/include/atomic_math.hpp:426:1:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/CoreEvaluators.h:960:8: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:181: gllvm.o] Error 1
ERROR: compilation failed for package ‘gllvm’
* removing ‘/tmp/workdir/gllvm/old/gllvm.Rcheck/gllvm’


```
# glmmfields

<details>

* Version: 0.1.4
* GitHub: https://github.com/seananderson/glmmfields
* Source code: https://github.com/cran/glmmfields
* Date/Publication: 2020-07-09 05:50:03 UTC
* Number of recursive dependencies: 93

Run `cloud_details(, "glmmfields")` for more info

</details>

## In both

*   checking whether package ‘glmmfields’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/glmmfields/new/glmmfields.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘glmmfields’ ...
** package ‘glmmfields’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
"/opt/R/4.0.3/lib/R/bin/Rscript" -e "source(file.path('..', 'tools', 'make_cc.R')); make_cc(commandArgs(TRUE))" stan_files/glmmfields.stan
Wrote C++ file "stan_files/glmmfields.cc"


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -fpic  -g -O2  -c stan_files/glmmfields.cc -o stan_files/glmmfields.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_glmmfields_namespace::model_glmmfields; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stan_files/glmmfields.o] Error 1
rm stan_files/glmmfields.cc
ERROR: compilation failed for package ‘glmmfields’
* removing ‘/tmp/workdir/glmmfields/new/glmmfields.Rcheck/glmmfields’


```
### CRAN

```
* installing *source* package ‘glmmfields’ ...
** package ‘glmmfields’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
"/opt/R/4.0.3/lib/R/bin/Rscript" -e "source(file.path('..', 'tools', 'make_cc.R')); make_cc(commandArgs(TRUE))" stan_files/glmmfields.stan
Wrote C++ file "stan_files/glmmfields.cc"


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -fpic  -g -O2  -c stan_files/glmmfields.cc -o stan_files/glmmfields.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_glmmfields_namespace::model_glmmfields; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stan_files/glmmfields.o] Error 1
rm stan_files/glmmfields.cc
ERROR: compilation failed for package ‘glmmfields’
* removing ‘/tmp/workdir/glmmfields/old/glmmfields.Rcheck/glmmfields’


```
# gWidgets2tcltk

<details>

* Version: 1.0-6
* GitHub: https://github.com/jverzani/gWidgets2tcltk
* Source code: https://github.com/cran/gWidgets2tcltk
* Date/Publication: 2018-09-25 13:20:02 UTC
* Number of recursive dependencies: 35

Run `cloud_details(, "gWidgets2tcltk")` for more info

</details>

## Newly broken

*   checking whether package ‘gWidgets2tcltk’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/gWidgets2tcltk/new/gWidgets2tcltk.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘gWidgets2tcltk’ ...
** package ‘gWidgets2tcltk’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** demo
** inst
** byte-compile and prepare package for lazy loading
Warning message:
In fun(libname, pkgname) : couldn't connect to display ":109"
Error in structure(.External(.C_dotTclObjv, objv), class = "tclObj") : 
  [tcl] invalid command name "font".

Error: unable to load R code in package ‘gWidgets2tcltk’
Execution halted
ERROR: lazy loading failed for package ‘gWidgets2tcltk’
* removing ‘/tmp/workdir/gWidgets2tcltk/new/gWidgets2tcltk.Rcheck/gWidgets2tcltk’


```
### CRAN

```
* installing *source* package ‘gWidgets2tcltk’ ...
** package ‘gWidgets2tcltk’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** demo
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (gWidgets2tcltk)


```
# hNMF

<details>

* Version: 1.0
* GitHub: NA
* Source code: https://github.com/cran/hNMF
* Date/Publication: 2020-11-20 13:30:02 UTC
* Number of recursive dependencies: 73

Run `cloud_details(, "hNMF")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/hNMF/new/hNMF.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘hNMF/DESCRIPTION’ ... OK
* this is package ‘hNMF’ version ‘1.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘NMF’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/hNMF/old/hNMF.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘hNMF/DESCRIPTION’ ... OK
* this is package ‘hNMF’ version ‘1.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘NMF’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# kdensity

<details>

* Version: 1.1.0
* GitHub: https://github.com/JonasMoss/kdensity
* Source code: https://github.com/cran/kdensity
* Date/Publication: 2020-09-30 09:00:05 UTC
* Number of recursive dependencies: 74

Run `cloud_details(, "kdensity")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/kdensity/new/kdensity.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘kdensity/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘kdensity’ version ‘1.1.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘univariateML’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/kdensity/old/kdensity.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘kdensity/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘kdensity’ version ‘1.1.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘univariateML’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# kmcudaR

<details>

* Version: 1.1.0
* GitHub: NA
* Source code: https://github.com/cran/kmcudaR
* Date/Publication: 2019-03-22 10:00:07 UTC
* Number of recursive dependencies: 35

Run `cloud_details(, "kmcudaR")` for more info

</details>

## In both

*   checking whether package ‘kmcudaR’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/kmcudaR/new/kmcudaR.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘kmcudaR’ ...
** package ‘kmcudaR’ successfully unpacked and MD5 sums checked
** using staged installation
checking for g++... g++
checking whether the C++ compiler works... yes
checking for C++ compiler default output file name... a.out
checking for suffix of executables... 
checking whether we are cross compiling... no
checking for suffix of object files... o
checking whether we are using the GNU C++ compiler... yes
...
checking whether g++ accepts -g... yes
checking how to run the C++ preprocessor... g++ -E
Checking for C++ Compiler
checking whether we are using the GNU C++ compiler... (cached) yes
checking whether g++ accepts -g... (cached) yes
checking "Checking environment variable CUDA_HOME"... "CUDA_HOME not set; using highest version found "
checking for /bin/nvcc... no
configure: error: "NVCC not found; check CUDA install"
ERROR: configuration failed for package ‘kmcudaR’
* removing ‘/tmp/workdir/kmcudaR/new/kmcudaR.Rcheck/kmcudaR’


```
### CRAN

```
* installing *source* package ‘kmcudaR’ ...
** package ‘kmcudaR’ successfully unpacked and MD5 sums checked
** using staged installation
checking for g++... g++
checking whether the C++ compiler works... yes
checking for C++ compiler default output file name... a.out
checking for suffix of executables... 
checking whether we are cross compiling... no
checking for suffix of object files... o
checking whether we are using the GNU C++ compiler... yes
...
checking whether g++ accepts -g... yes
checking how to run the C++ preprocessor... g++ -E
Checking for C++ Compiler
checking whether we are using the GNU C++ compiler... (cached) yes
checking whether g++ accepts -g... (cached) yes
checking "Checking environment variable CUDA_HOME"... "CUDA_HOME not set; using highest version found "
checking for /bin/nvcc... no
configure: error: "NVCC not found; check CUDA install"
ERROR: configuration failed for package ‘kmcudaR’
* removing ‘/tmp/workdir/kmcudaR/old/kmcudaR.Rcheck/kmcudaR’


```
# lgpr

<details>

* Version: 1.1.4
* GitHub: https://github.com/jtimonen/lgpr
* Source code: https://github.com/cran/lgpr
* Date/Publication: 2021-08-11 05:00:01 UTC
* Number of recursive dependencies: 92

Run `cloud_details(, "lgpr")` for more info

</details>

## In both

*   checking whether package ‘lgpr’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/lgpr/new/lgpr.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘lgpr’ ...
** package ‘lgpr’ successfully unpacked and MD5 sums checked
** using staged installation
** libs


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -D_REENTRANT -DSTAN_THREADS   -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:13,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/ProductEvaluators.h:35:90:   required from ‘Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::evaluator(const XprType&) [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Options = 0; Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::XprType = Eigen::Product<Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>, Eigen::Matrix<double, -1, 1>, 0>]’
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_lgp_namespace::model_lgp; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stanExports_lgp.o] Error 1
ERROR: compilation failed for package ‘lgpr’
* removing ‘/tmp/workdir/lgpr/new/lgpr.Rcheck/lgpr’


```
### CRAN

```
* installing *source* package ‘lgpr’ ...
** package ‘lgpr’ successfully unpacked and MD5 sums checked
** using staged installation
** libs


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -D_REENTRANT -DSTAN_THREADS   -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:13,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/ProductEvaluators.h:35:90:   required from ‘Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::evaluator(const XprType&) [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Options = 0; Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::XprType = Eigen::Product<Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>, Eigen::Matrix<double, -1, 1>, 0>]’
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_lgp_latent_namespace::model_lgp_latent; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stanExports_lgp_latent.o] Error 1
ERROR: compilation failed for package ‘lgpr’
* removing ‘/tmp/workdir/lgpr/old/lgpr.Rcheck/lgpr’


```
# loon

<details>

* Version: 1.3.7
* GitHub: https://github.com/great-northern-diver/loon
* Source code: https://github.com/cran/loon
* Date/Publication: 2021-06-14 06:20:02 UTC
* Number of recursive dependencies: 95

Run `cloud_details(, "loon")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/loon/new/loon.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘loon/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘loon’ version ‘1.3.7’
* package encoding: UTF-8
* checking package namespace information ... OK
...
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘introduction.Rmd’ using ‘UTF-8’... OK
  ‘logicalQueries.Rmd’ using ‘UTF-8’... OK
  ‘minorities.Rmd’ using ‘UTF-8’... OK
  ‘savingLoonPlots.Rmd’ using ‘UTF-8’... OK
  ‘teaching-example-smoothing.Rmd’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 1 NOTE





```
### CRAN

```
* using log directory ‘/tmp/workdir/loon/old/loon.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘loon/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘loon’ version ‘1.3.7’
* package encoding: UTF-8
* checking package namespace information ... OK
...
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘introduction.Rmd’ using ‘UTF-8’... OK
  ‘logicalQueries.Rmd’ using ‘UTF-8’... OK
  ‘minorities.Rmd’ using ‘UTF-8’... OK
  ‘savingLoonPlots.Rmd’ using ‘UTF-8’... OK
  ‘teaching-example-smoothing.Rmd’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 1 NOTE





```
# loon.shiny

<details>

* Version: 1.0.0
* GitHub: NA
* Source code: https://github.com/cran/loon.shiny
* Date/Publication: 2021-06-10 16:30:06 UTC
* Number of recursive dependencies: 133

Run `cloud_details(, "loon.shiny")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/loon.shiny/new/loon.shiny.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘loon.shiny/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘loon.shiny’ version ‘1.0.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'loon', 'loon.ggplot'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/loon.shiny/old/loon.shiny.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘loon.shiny/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘loon.shiny’ version ‘1.0.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'loon', 'loon.ggplot'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# loon.tourr

<details>

* Version: 0.1.2
* GitHub: https://github.com/z267xu/loon.tourr
* Source code: https://github.com/cran/loon.tourr
* Date/Publication: 2021-07-25 20:40:03 UTC
* Number of recursive dependencies: 118

Run `cloud_details(, "loon.tourr")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/loon.tourr/new/loon.tourr.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘loon.tourr/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘loon.tourr’ version ‘0.1.2’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'loon', 'loon.ggplot'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/loon.tourr/old/loon.tourr.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘loon.tourr/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘loon.tourr’ version ‘0.1.2’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'loon', 'loon.ggplot'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# mcmcabn

<details>

* Version: 0.4
* GitHub: NA
* Source code: https://github.com/cran/mcmcabn
* Date/Publication: 2021-06-02 06:10:01 UTC
* Number of recursive dependencies: 136

Run `cloud_details(, "mcmcabn")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/mcmcabn/new/mcmcabn.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘mcmcabn/DESCRIPTION’ ... OK
* this is package ‘mcmcabn’ version ‘0.4’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'gRbase', 'abn'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/mcmcabn/old/mcmcabn.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘mcmcabn/DESCRIPTION’ ... OK
* this is package ‘mcmcabn’ version ‘0.4’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'gRbase', 'abn'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# metagam

<details>

* Version: 0.2.0
* GitHub: https://github.com/Lifebrain/metagam
* Source code: https://github.com/cran/metagam
* Date/Publication: 2020-11-12 08:10:02 UTC
* Number of recursive dependencies: 145

Run `cloud_details(, "metagam")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/metagam/new/metagam.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘metagam/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘metagam’ version ‘0.2.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘metap’

Package suggested but not available for checking: ‘multtest’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/metagam/old/metagam.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘metagam/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘metagam’ version ‘0.2.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘metap’

Package suggested but not available for checking: ‘multtest’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# mlpack

<details>

* Version: 3.4.2.1
* GitHub: https://github.com/mlpack/mlpack
* Source code: https://github.com/cran/mlpack
* Date/Publication: 2020-12-18 23:20:02 UTC
* Number of recursive dependencies: 35

Run `cloud_details(, "mlpack")` for more info

</details>

## In both

*   checking whether package ‘mlpack’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/mlpack/new/mlpack.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘mlpack’ ...
** package ‘mlpack’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppArmadillo/include' -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEnsmallen/include' -I/usr/local/include  -DBOOST_MATH_PROMOTE_DOUBLE_POLICY=false -I. -fopenmp -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/BH/include/boost/scoped_ptr.hpp:13,
                 from /opt/R/4.0.3/lib/R/site-library/BH/include/boost/archive/detail/basic_iarchive.hpp:23,
                 from ./boost/serialization/unordered_collections_load_imp.hpp:36,
                 from ./boost/serialization/unordered_map.hpp:30,
                 from ./mlpack/core/boost_backport/boost_backport_serialization.hpp:19,
...
                 from ./rcpp_mlpack.h:16,
                 from cf.cpp:7:
/usr/include/c++/9/bits/unique_ptr.h:53:28: note: declared here
   53 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:181: cf.o] Error 1
ERROR: compilation failed for package ‘mlpack’
* removing ‘/tmp/workdir/mlpack/new/mlpack.Rcheck/mlpack’


```
### CRAN

```
* installing *source* package ‘mlpack’ ...
** package ‘mlpack’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
g++ -std=gnu++11 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG  -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppArmadillo/include' -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEnsmallen/include' -I/usr/local/include  -DBOOST_MATH_PROMOTE_DOUBLE_POLICY=false -I. -fopenmp -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/BH/include/boost/scoped_ptr.hpp:13,
                 from /opt/R/4.0.3/lib/R/site-library/BH/include/boost/archive/detail/basic_iarchive.hpp:23,
                 from ./boost/serialization/unordered_collections_load_imp.hpp:36,
                 from ./boost/serialization/unordered_map.hpp:30,
                 from ./mlpack/core/boost_backport/boost_backport_serialization.hpp:19,
...
                 from ./rcpp_mlpack.h:16,
                 from cf.cpp:7:
/usr/include/c++/9/bits/unique_ptr.h:53:28: note: declared here
   53 |   template<typename> class auto_ptr;
      |                            ^~~~~~~~
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:181: cf.o] Error 1
ERROR: compilation failed for package ‘mlpack’
* removing ‘/tmp/workdir/mlpack/old/mlpack.Rcheck/mlpack’


```
# osmplotr

<details>

* Version: 0.3.3
* GitHub: https://github.com/ropensci/osmplotr
* Source code: https://github.com/cran/osmplotr
* Date/Publication: 2021-03-28 00:10:03 UTC
* Number of recursive dependencies: 94

Run `cloud_details(, "osmplotr")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/osmplotr/new/osmplotr.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘osmplotr/DESCRIPTION’ ... OK
* this is package ‘osmplotr’ version ‘0.3.3’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘ggm’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/osmplotr/old/osmplotr.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘osmplotr/DESCRIPTION’ ... OK
* this is package ‘osmplotr’ version ‘0.3.3’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘ggm’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# penaltyLearning

<details>

* Version: 2020.5.13
* GitHub: https://github.com/tdhock/penaltyLearning
* Source code: https://github.com/cran/penaltyLearning
* Date/Publication: 2020-05-14 16:20:02 UTC
* Number of recursive dependencies: 60

Run `cloud_details(, "penaltyLearning")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/penaltyLearning/new/penaltyLearning.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘penaltyLearning/DESCRIPTION’ ... OK
* this is package ‘penaltyLearning’ version ‘2020.5.13’
* checking package namespace information ... OK
* checking package dependencies ... NOTE
Package suggested but not available for checking: ‘jointseg’
...
* checking for GNU extensions in Makefiles ... OK
* checking for portable use of $(BLAS_LIBS) and $(LAPACK_LIBS) ... OK
* checking use of PKG_*FLAGS in Makefiles ... OK
* checking compiled code ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* DONE
Status: 1 NOTE





```
### CRAN

```
* using log directory ‘/tmp/workdir/penaltyLearning/old/penaltyLearning.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘penaltyLearning/DESCRIPTION’ ... OK
* this is package ‘penaltyLearning’ version ‘2020.5.13’
* checking package namespace information ... OK
* checking package dependencies ... NOTE
Package suggested but not available for checking: ‘jointseg’
...
* checking for GNU extensions in Makefiles ... OK
* checking for portable use of $(BLAS_LIBS) and $(LAPACK_LIBS) ... OK
* checking use of PKG_*FLAGS in Makefiles ... OK
* checking compiled code ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* DONE
Status: 1 NOTE





```
# phylopath

<details>

* Version: 1.1.2
* GitHub: https://github.com/Ax3man/phylopath
* Source code: https://github.com/cran/phylopath
* Date/Publication: 2019-12-07 01:10:07 UTC
* Number of recursive dependencies: 90

Run `cloud_details(, "phylopath")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/phylopath/new/phylopath.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘phylopath/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘phylopath’ version ‘1.1.2’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘ggm’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/phylopath/old/phylopath.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘phylopath/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘phylopath’ version ‘1.1.2’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘ggm’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# ReIns

<details>

* Version: 1.0.10
* GitHub: https://github.com/TReynkens/ReIns
* Source code: https://github.com/cran/ReIns
* Date/Publication: 2020-05-17 00:00:02 UTC
* Number of recursive dependencies: 55

Run `cloud_details(, "ReIns")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/ReIns/new/ReIns.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘ReIns/DESCRIPTION’ ... OK
* this is package ‘ReIns’ version ‘1.0.10’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘ReIns.Rmd’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 3 NOTEs





```
### CRAN

```
* using log directory ‘/tmp/workdir/ReIns/old/ReIns.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘ReIns/DESCRIPTION’ ... OK
* this is package ‘ReIns’ version ‘1.0.10’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... NOTE
...
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* checking for unstated dependencies in vignettes ... OK
* checking package vignettes in ‘inst/doc’ ... OK
* checking running R code from vignettes ... NONE
  ‘ReIns.Rmd’ using ‘UTF-8’... OK
* checking re-building of vignette outputs ... SKIPPED
* DONE
Status: 3 NOTEs





```
# rmdcev

<details>

* Version: 1.2.4
* GitHub: https://github.com/plloydsmith/rmdcev
* Source code: https://github.com/cran/rmdcev
* Date/Publication: 2020-09-30 18:40:02 UTC
* Number of recursive dependencies: 82

Run `cloud_details(, "rmdcev")` for more info

</details>

## In both

*   checking whether package ‘rmdcev’ can be installed ... ERROR
    ```
    Installation failed.
    See ‘/tmp/workdir/rmdcev/new/rmdcev.Rcheck/00install.out’ for details.
    ```

## Installation

### Devel

```
* installing *source* package ‘rmdcev’ ...
** package ‘rmdcev’ successfully unpacked and MD5 sums checked
** using staged installation
** libs


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -D_REENTRANT -DSTAN_THREADS   -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:13,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/ProductEvaluators.h:35:90:   required from ‘Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::evaluator(const XprType&) [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Options = 0; Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::XprType = Eigen::Product<Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>, Eigen::Matrix<double, -1, 1>, 0>]’
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_mdcev_namespace::model_mdcev; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stanExports_mdcev.o] Error 1
ERROR: compilation failed for package ‘rmdcev’
* removing ‘/tmp/workdir/rmdcev/new/rmdcev.Rcheck/rmdcev’


```
### CRAN

```
* installing *source* package ‘rmdcev’ ...
** package ‘rmdcev’ successfully unpacked and MD5 sums checked
** using staged installation
** libs


g++ -std=gnu++14 -I"/opt/R/4.0.3/lib/R/include" -DNDEBUG -I"../inst/include" -I"/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src" -DBOOST_DISABLE_ASSERTS -DEIGEN_NO_DEBUG -DBOOST_MATH_OVERFLOW_ERROR_POLICY=errno_on_error -I'/opt/R/4.0.3/lib/R/site-library/BH/include' -I'/opt/R/4.0.3/lib/R/site-library/Rcpp/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppEigen/include' -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -I'/opt/R/4.0.3/lib/R/site-library/rstan/include' -I'/opt/R/4.0.3/lib/R/site-library/StanHeaders/include' -I/usr/local/include   -I'/opt/R/4.0.3/lib/R/site-library/RcppParallel/include' -D_REENTRANT -DSTAN_THREADS   -fpic  -g -O2  -c RcppExports.cpp -o RcppExports.o
In file included from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Core:397,
                 from /opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/Dense:1,
                 from /opt/R/4.0.3/lib/R/site-library/StanHeaders/include/stan/math/prim/mat/fun/Eigen.hpp:13,
...
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/ProductEvaluators.h:35:90:   required from ‘Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::evaluator(const XprType&) [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Options = 0; Eigen::internal::evaluator<Eigen::Product<Lhs, Rhs, Option> >::XprType = Eigen::Product<Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>, Eigen::Matrix<double, -1, 1>, 0>]’
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/Product.h:132:22:   required from ‘Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::operator const Scalar() const [with Lhs = Eigen::Product<Eigen::CwiseBinaryOp<Eigen::internal::scalar_product_op<double, double>, const Eigen::CwiseNullaryOp<Eigen::internal::scalar_constant_op<double>, const Eigen::Matrix<double, 1, -1> >, const Eigen::Transpose<Eigen::Matrix<double, -1, 1> > >, Eigen::Matrix<double, -1, -1>, 0>; Rhs = Eigen::Matrix<double, -1, 1>; int Option = 0; Eigen::internal::dense_product_base<Lhs, Rhs, Option, 6>::Scalar = double]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:23:56:   required from ‘double stan::mcmc::dense_e_metric<Model, BaseRNG>::T(stan::mcmc::dense_e_point&) [with Model = model_mdcev_namespace::model_mdcev; BaseRNG = boost::random::additive_combine_engine<boost::random::linear_congruential_engine<unsigned int, 40014, 0, 2147483563>, boost::random::linear_congruential_engine<unsigned int, 40692, 0, 2147483399> >]’
/opt/R/4.0.3/lib/R/site-library/StanHeaders/include/src/stan/mcmc/hmc/hamiltonians/dense_e_metric.hpp:22:10:   required from here
/opt/R/4.0.3/lib/R/site-library/RcppEigen/include/Eigen/src/Core/DenseCoeffsBase.h:55:30: warning: ignoring attributes on template argument ‘Eigen::internal::packet_traits<double>::type’ {aka ‘__vector(2) double’} [-Wignored-attributes]
g++: fatal error: Killed signal terminated program cc1plus
compilation terminated.
make: *** [/opt/R/4.0.3/lib/R/etc/Makeconf:179: stanExports_mdcev.o] Error 1
ERROR: compilation failed for package ‘rmdcev’
* removing ‘/tmp/workdir/rmdcev/old/rmdcev.Rcheck/rmdcev’


```
# scoper

<details>

* Version: 1.1.0
* GitHub: NA
* Source code: https://github.com/cran/scoper
* Date/Publication: 2020-08-10 21:50:02 UTC
* Number of recursive dependencies: 119

Run `cloud_details(, "scoper")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/scoper/new/scoper.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘scoper/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘scoper’ version ‘1.1.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'alakazam', 'shazam'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/scoper/old/scoper.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘scoper/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘scoper’ version ‘1.1.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'alakazam', 'shazam'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# seqgendiff

<details>

* Version: 1.2.2
* GitHub: https://github.com/dcgerard/seqgendiff
* Source code: https://github.com/cran/seqgendiff
* Date/Publication: 2020-05-24 19:20:05 UTC
* Number of recursive dependencies: 136

Run `cloud_details(, "seqgendiff")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/seqgendiff/new/seqgendiff.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘seqgendiff/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘seqgendiff’ version ‘1.2.2’
* package encoding: UTF-8
* checking package namespace information ... OK
...
Packages required but not available: 'sva', 'cate'

Packages suggested but not available for checking:
  'SummarizedExperiment', 'DESeq2', 'airway', 'limma', 'qvalue',
  'edgeR'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/seqgendiff/old/seqgendiff.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘seqgendiff/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘seqgendiff’ version ‘1.2.2’
* package encoding: UTF-8
* checking package namespace information ... OK
...
Packages required but not available: 'sva', 'cate'

Packages suggested but not available for checking:
  'SummarizedExperiment', 'DESeq2', 'airway', 'limma', 'qvalue',
  'edgeR'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# shattering

<details>

* Version: 1.0.6
* GitHub: NA
* Source code: https://github.com/cran/shattering
* Date/Publication: 2021-06-02 23:00:02 UTC
* Number of recursive dependencies: 84

Run `cloud_details(, "shattering")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/shattering/new/shattering.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘shattering/DESCRIPTION’ ... OK
* this is package ‘shattering’ version ‘1.0.6’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘NMF’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/shattering/old/shattering.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘shattering/DESCRIPTION’ ... OK
* this is package ‘shattering’ version ‘1.0.6’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘NMF’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# SMITIDvisu

<details>

* Version: 0.0.9
* GitHub: NA
* Source code: https://github.com/cran/SMITIDvisu
* Date/Publication: 2021-02-08 08:50:03 UTC
* Number of recursive dependencies: 90

Run `cloud_details(, "SMITIDvisu")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/SMITIDvisu/new/SMITIDvisu.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘SMITIDvisu/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘SMITIDvisu’ version ‘0.0.9’
* package encoding: UTF-8
* checking package namespace information ... OK
...
* checking data for non-ASCII characters ... OK
* checking data for ASCII and uncompressed saves ... OK
* checking line endings in C/C++/Fortran sources/headers ... OK
* checking compiled code ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* DONE
Status: 1 NOTE





```
### CRAN

```
* using log directory ‘/tmp/workdir/SMITIDvisu/old/SMITIDvisu.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘SMITIDvisu/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘SMITIDvisu’ version ‘0.0.9’
* package encoding: UTF-8
* checking package namespace information ... OK
...
* checking data for non-ASCII characters ... OK
* checking data for ASCII and uncompressed saves ... OK
* checking line endings in C/C++/Fortran sources/headers ... OK
* checking compiled code ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* DONE
Status: 1 NOTE





```
# spectralAnalysis

<details>

* Version: 3.12.0
* GitHub: NA
* Source code: https://github.com/cran/spectralAnalysis
* Date/Publication: 2018-06-12 14:30:39 UTC
* Number of recursive dependencies: 104

Run `cloud_details(, "spectralAnalysis")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/spectralAnalysis/new/spectralAnalysis.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘spectralAnalysis/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘spectralAnalysis’ version ‘3.12.0’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'BiocGenerics', 'NMF', 'hNMF'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/spectralAnalysis/old/spectralAnalysis.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘spectralAnalysis/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘spectralAnalysis’ version ‘3.12.0’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'BiocGenerics', 'NMF', 'hNMF'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# stablespec

<details>

* Version: 0.3.0
* GitHub: https://github.com/rahmarid/stablespec
* Source code: https://github.com/cran/stablespec
* Date/Publication: 2017-04-05 03:27:52 UTC
* Number of recursive dependencies: 97

Run `cloud_details(, "stablespec")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/stablespec/new/stablespec.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘stablespec/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘stablespec’ version ‘0.3.0’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'ggm', 'graph', 'Rgraphviz'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/stablespec/old/stablespec.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘stablespec/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘stablespec’ version ‘0.3.0’
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'ggm', 'graph', 'Rgraphviz'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# superb

<details>

* Version: 0.9.7.5
* GitHub: https://github.com/dcousin3/superb
* Source code: https://github.com/cran/superb
* Date/Publication: 2021-06-23 04:10:02 UTC
* Number of recursive dependencies: 162

Run `cloud_details(, "superb")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/superb/new/superb.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘superb/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘superb’ version ‘0.9.7.5’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘referenceIntervals’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/superb/old/superb.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘superb/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘superb’ version ‘0.9.7.5’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Package required but not available: ‘referenceIntervals’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# tigger

<details>

* Version: 1.0.0
* GitHub: NA
* Source code: https://github.com/cran/tigger
* Date/Publication: 2020-05-13 05:10:03 UTC
* Number of recursive dependencies: 120

Run `cloud_details(, "tigger")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/tigger/new/tigger.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘tigger/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘tigger’ version ‘1.0.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'alakazam', 'shazam'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
### CRAN

```
* using log directory ‘/tmp/workdir/tigger/old/tigger.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘tigger/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘tigger’ version ‘1.0.0’
* package encoding: UTF-8
* checking package namespace information ... OK
* checking package dependencies ... ERROR
Packages required but not available: 'alakazam', 'shazam'

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
* DONE
Status: 1 ERROR





```
# wrswoR

<details>

* Version: 1.1.1
* GitHub: https://github.com/krlmlr/wrswoR
* Source code: https://github.com/cran/wrswoR
* Date/Publication: 2020-07-26 18:20:02 UTC
* Number of recursive dependencies: 134

Run `cloud_details(, "wrswoR")` for more info

</details>

## Error before installation

### Devel

```
* using log directory ‘/tmp/workdir/wrswoR/new/wrswoR.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘wrswoR/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘wrswoR’ version ‘1.1.1’
* package encoding: UTF-8
* checking package namespace information ... OK
...
* checking for GNU extensions in Makefiles ... OK
* checking for portable use of $(BLAS_LIBS) and $(LAPACK_LIBS) ... OK
* checking use of PKG_*FLAGS in Makefiles ... OK
* checking compiled code ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* DONE
Status: 1 NOTE





```
### CRAN

```
* using log directory ‘/tmp/workdir/wrswoR/old/wrswoR.Rcheck’
* using R version 4.0.3 (2020-10-10)
* using platform: x86_64-pc-linux-gnu (64-bit)
* using session charset: UTF-8
* using options ‘--no-manual --no-build-vignettes’
* checking for file ‘wrswoR/DESCRIPTION’ ... OK
* checking extension type ... Package
* this is package ‘wrswoR’ version ‘1.1.1’
* package encoding: UTF-8
* checking package namespace information ... OK
...
* checking for GNU extensions in Makefiles ... OK
* checking for portable use of $(BLAS_LIBS) and $(LAPACK_LIBS) ... OK
* checking use of PKG_*FLAGS in Makefiles ... OK
* checking compiled code ... OK
* checking examples ... OK
* checking for unstated dependencies in ‘tests’ ... OK
* checking tests ... OK
  Running ‘testthat.R’
* DONE
Status: 1 NOTE





```
