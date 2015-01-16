# How to run
`<path-to-node>` tsc.js -out out.js --diagnostics src/services/typescriptServices.ts

# Local results (no disk I\O in emit)
/home/v2m/.nvm/v0.10.35/bin/node
- Parse time: 	AVG:	0.866	STDDEV:	0.0048990	BEST:	0.86	WORST:	0.87
- Bind time:	AVG:	0.312	STDDEV:	0.0040000	BEST:	0.31	WORST:	0.32
- Check time:	AVG:	1.552	STDDEV:	0.0263818	BEST:	1.52	WORST:	1.6
- Emit time:	AVG:	0.4	STDDEV:	0.0063246	BEST:	0.39	WORST:	0.41
- (AVG) Total time:	3.13

/home/v2m/.nvm/v0.11.14/bin/node
- Parse time: 	AVG:	0.952	STDDEV:	0.0318748	BEST:	0.91	WORST:	0.99
- Bind time:	AVG:	0.434	STDDEV:	0.0101980	BEST:	0.42	WORST:	0.45
- Check time:	AVG:	1.634	STDDEV:	0.0257682	BEST:	1.6	WORST:	1.67
- Emit time:	AVG:	0.494	STDDEV:	0.0080000	BEST:	0.48	WORST:	0.5
- (AVG) Total time:	3.514

/home/v2m/code/iojs-v1.0.1-linux-x64/bin/node
- Parse time: 	AVG:	0.778	STDDEV:	0.0074833	BEST:	0.77	WORST:	0.79
- Bind time:	AVG:	0.346	STDDEV:	0.0048990	BEST:	0.34	WORST:	0.35
- Check time:	AVG:	2.088	STDDEV:	0.0116619	BEST:	2.07	WORST:	2.1
- Emit time:	AVG:	0.596	STDDEV:	0.0135647	BEST:	0.58	WORST:	0.61
- (AVG) Total time:	3.808
	