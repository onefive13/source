.. bros. documentation master file, created by
   sphinx-quickstart on Mon Mar  8 11:45:36 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to MENOTES!
=================================

このページではLinuxやviといったコンピューターシミュレーションの基礎から、MDのソフト・ツールまで幅広く説明しています。

.. hint::
   2022/10/13 高分子の記事を追記しました。

   2022/09/02 先輩のウェブサイトと統合しました。

   2021/06/01 新しくホームページを作りました。

.. toctree::
   :maxdepth: 1
   :caption: Linux

   ./LINUX/linux1
   ./LINUX/linuxq1
   ./LINUX/linuxcommand
   ./LINUX/vim_0
   ./LINUX/ssh

.. toctree::
   :maxdepth: 1
   :caption: Simulation Introduction

   /GROMACS/GROMACSinstall.md
   /GROMACS/GROMACSindex1.rst
   /GROMACS/GROMACSindex2.rst
   /GROMACS/GROMACSmdp.md
   /VMD/VMDindex.rst
   /GNUPLOT/GNUPLOTusage.md

.. toctree::
   :maxdepth: 1
   :caption: Molecular Dynamics

   ./MD/mdsoft
   ./MD/gromacs
   ./MD/namd
   ./MD/lammps
   ./MD/mpdyn
   ./plot/Gnuplot_01
   ./MD/vmd
   ./MD/Discovery_studio
   ./MD/fftw
   ./MD/plumed
   ./MD/packmol
   ./MD/MPI

.. toctree::
   :maxdepth: 1
   :caption: POLYMER

   /Polymer/polymer_property.rst

.. toctree::
   :maxdepth: 1
   :caption: Tools

   ./slack/insto
   ./device/main
   ./make_homepages/how_to_use_git
   ./make_homepages/sandbox
   /SPHINX/sphinxindex.rst
   /GIT/gitindex.rst
..   /trip/trip


.. toctree::
   :maxdepth: 1
   :caption: Cheat sheet

   /GROMACS/GROMACScheat.md
   /VMD/VMDcheat.md


.. toctree::
   :maxdepth: 1
   :caption: Python Room

   ./python/matplotlib
   ./python/MDAnalysis
   ./python/MDAnalysis_tutorial
   ./python/anaconda

