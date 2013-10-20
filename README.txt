<ID>.json contains the balance data for that particular build ID. You can get the build ID for a given replay from Spawning Tool by doing

	import spawningtool
	parsed = spawningtool.parser.parse_replay(replayfile)
	ID = parsed['baseBuild']

:)