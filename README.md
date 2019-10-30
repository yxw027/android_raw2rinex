# Usage

## function

convert raw/fix data generated by GnssLogger into standard observation format(Version Rinex 3.x)

## android_raw2rinex

raw2rinex.py -c <confgure file>

## configure file

dir_path : directory of raw file
raw_path : raw file name
type     : FIX / RAW


## mode

*FIX:

Get positioning results by android inner algorithm.

Output `*.out` file with format `YYYY/mm/dd HH:MM:SS X Y Z`

*RAW:

Convert raw data to rinex 3.x format.

Output `*.o` file.

## reference

Android GNSS raw measurements[https://gnss-compare.readthedocs.io/en/latest/user_manual/android_gnssMeasurements.html?tdsourcetag=s_pctim_aiomsg].
