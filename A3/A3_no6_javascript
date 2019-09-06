var results = document.getElementById('piggize-results');

// convert the word to pig then print
function printLatinWord(word) {
	results.innerHTML+= word.substring(1) + word[0] + 'ay ';
}

// convert the sentence to pig
function pig() {
	var input = document.getElementById('size-input');
	var words = input.value.split(' ');

	// print each word in pig latin
	words.forEach(printLatinWord);
	results.innerHTML+= "\n";
}

document.getElementById('piggizebutton').onclick = function(e) {
	e.preventDefault();
	pig();
}
