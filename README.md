# iptable_snapshot
the real flow entry in real routers
* Data Format

<>(Once unpacked (with gunzip or gzip -d for example), these files can be used
directly with CAIDA's ASFinder and various CoralReef tools (such as the
t2_convert -R option).  For more information about these tools see
http://www.caida.org/tools/measurement/coralreef/)

The file format is line-oriented, with one prefix-AS mapping per line.  The
tab-separated fields are

   * IP prefix
   * prefix length
   * AS

The AS can be a single AS number, an AS set (e.g. {32,54} ), or a multi-origin 
AS (e.g. 10_20 ).
