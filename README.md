# RxJava 2 built with JDK 8, 9, 10, 11, 12 and 13

<a href='https://travis-ci.org/akarnokd/RxJava2_9/builds'><img src='https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master'></a>
[![codecov.io](http://codecov.io/github/akarnokd/RxJava2_9/coverage.svg?branch=master)](https://codecov.io/gh/akarnokd/RxJava2_9/branch/master)

This repository is used for building [RxJava 2](https://github.com/ReactiveX/RxJava) with JDK 8, 9, 10, 11 and 12 in a CI environment. 

It **does not use the JDK 9 `Flow` API** nor does this repo create maven jars.

This repo doesn't produce maven artifacts of the builds as the only purpose is to cross test RxJava **and** the mainstream/upcoming JDKs.

### Build matrix

JDK runtime | Target 6 | Target 8 | Target 9 | Target 10 | Target 11 | Target 12 | Target 13
-|----|---|------|------|------|----------|----------|
8 | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/1)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/2)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master)
9 | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/3)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/4)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/5)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master)
10 | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/6)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/7)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/8)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/9)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master)
11 | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/10)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/11)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/12)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/13)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/14)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master)
12 | N/A | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/15)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/16)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/17)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/18)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/19)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master)
13 | N/A | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/20)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/21)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/22)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/23)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/24)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master) | [![image](https://travis-matrix-badges.herokuapp.com/repos/akarnokd/RxJava2_9/branches/master/25)](https://travis-ci.org/akarnokd/RxJava2_9.svg?branch=master)

#### Note on JDK target support

With the newest JDKs, certain older compile targets are no longer supported. JDK 12 dropped 6 support and JDK drops 7 support.