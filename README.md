# jMeter_test

1. Put floodIOtest.jmx file and testData folder to bin directory (jMeter home)
2. Run from command line:
	jmeter -n -t floodIOtest.jmx -Jthreads=3 -Jrampup=2

Summary Report provided in file SummaryReport_Threads20_Rampup5.csv