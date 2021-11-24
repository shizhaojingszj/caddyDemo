run:
	pm2 delete s1 || echo 1
	pm2 delete s2 || echo 1
	pm2 delete s3 || echo 1
	pm2 start --name s1 'serve -s 1 -p 9001'
	pm2 start --name s2 'serve -s 2 -p 9002'
	pm2 start --name s3 'serve -s 3 -p 9003'