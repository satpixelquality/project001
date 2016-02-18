# project001
windows application for cris data quality visualization using C# and HTML5
input data is from 
 ftp://ftp.star.nesdis.noaa.gov/pub/smcd/spb/xjin/icvs/json/npp/${yyyy}/${yyyymmdd}_CRIS.FSR.json.gz
and 
 ftp://ftp.star.nesdis.noaa.gov/pub/smcd/spb/xjin/icvs/json/npp/${yyyy}/${yyyymmdd}_CRIS.SDR.json.gz

they are derivatives of NOAA/STAR ICVS SNPP/CrIS IDPS-SDR and FSR-SDR quality monitoring system

Only display those pixels whose overall data quality flags are set.

The interface is a Windows WPF window embedded with a 2D google map.
