# List of languages Google's speech to text API supports in BCP-47 format
Simple sed command to extract a list of languages Google's speech to text API supports (in BCP-47 format)

## Instructions to run
1. Go to https://cloud.google.com/speech-to-text/docs/languages and copy the table of supported languages into a file named `supportedLangs.txt`
2. Run the `extractor` shell script
3. This will produce a file called `supportedLocales.txt` which contains the extracted BCP-47 codes
