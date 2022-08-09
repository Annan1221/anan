 giftCode = function () {
		    let code = "";
		    let letters = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789";
	for (var i = 0; i < 24; i++) {
		code = code + letters.charAt(Math.floor(Math.random() * letters.length));
    	}
	return code;
    }
   
