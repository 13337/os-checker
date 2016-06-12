#! /usr/bin/nodejs

// This script checks the user's OS and offers its two cents.

var os = require('os');

function osChecker() {
	var plat = os.platform();
	var assesment = "You use " + plat + "? ";

	switch (plat) {
		case 'freebsd':
		case 'sunos':
		case 'linux':
			console.log(assesment + 'cool, cool, cool!');
			break;
		case 'win32':
			console.log(assesment + 'lol, get a real OS');
			break;

		default:
			// using .concat this time because don't tell me how to live my life, dude.
			console.log(assesment.concat('yeah, whatever man'));
			break;
	}
}

osChecker();

