# GCS filter
A browser-compatible implementation of GCS filters

# What is this?
I just took this library: https://github.com/bcoin-org/golomb and used webpack to make it compatible with the web browser

# Why did you do this?
It is part of my quest to make a browser wallet based on Bip157 Compact Block Filters. Bip157 uses Golumb Coded Sets to construct its filters, and the lovely folks at bcoin made a library for using them. I just ported the library for use in web browsers, except I hard coded the P value required by bip157, where theirs is configurable.

# How an I use it?
Just click here and open your browser console to view the magic: https://supertestnet.github.io/gcs_filter
