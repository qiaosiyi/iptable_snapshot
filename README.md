# iptable_snapshot
A set of ip table flow entries in a AS core router

snapshot TIME: 1 Jan 2019

* Data Format


The file format is line-oriented, with one prefix-AS mapping per line.  The
tab-separated fields are

   * IP prefix
   * prefix length
   * AS

The AS can be a single AS number, an AS set (e.g. {32,54} ), or a multi-origin 
AS (e.g. 10_20 ).
