# X12Parser-laravel-class
A Laravel PHP class that parses and interprets simple X12 messages


example of use:


use App\Services\X12Parser;

$x12Message = '...'; // Your X12 message
$parser = new X12Parser($x12Message);

// To get the data as a JSON object
$json = $parser->toJSON();

// To get the data as a key-value array
$array = $parser->toArray();
