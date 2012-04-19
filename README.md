<h1>check-rbl</h1>

Check if an IP is listed on the most used RBL

<h3>Usage of check-rbl.pl:</h3>

Required parameters:
        -i,--ip         The IP to check
        -q,--quiet      Quiet mode

        -h,--help       Show help

    Report bugs or ask for new options: https://github.com/DjinnS/check-rbl

<h3>Example:</h3>

	$ perl check-rbl.pl -i 8.8.8.8
	8.8.8.8 isn't listed on any RBL.

Exit code is 0 if not, 1 if listed.
