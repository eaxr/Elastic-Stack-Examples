# Elastic-Stack-Examples
some examples

input file:

cat /var/log/dpkg.log
2020-02-20 09:03:27 status installed cowsay:all 3.03+dfsg2-6

table from kibana:

@timestamp	Feb 20, 2020 @ 06:03:35.993
	_index	dpkg_logs
	_score	 - 
	_type	_doc
	agent.type	filebeat
	agent.version	7.6.0
	command	installed
	day	20
	ecs.version	1.4.0
	input.type	log
	log.file.path	/var/log/dpkg.log
	log.offset	833,625
	month	02
	package	cowsay:all 3.03+dfsg2-6
	status	status
	time	09:03:27
	year	2020
