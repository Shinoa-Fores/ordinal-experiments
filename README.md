# ordinal-experiments

`inscriptions-parser.py` is a simple Python script that extracts the raw inscription data from the taproot witness data and generates a binary output file with the results.

To use the inscriptions parser script:

1. Find your inscription tx on a bitcoin explorer i.e. https://mempool.space
2. Find the witness data in the tx details
3. Copy the witness data hex
4. Paste the witness data hex in the `witness_data` variable within the `inscriptions-parser.py` script
5. Run the script using `python inscriptions-parser.py`
6. Append the appropiate file extension to the output file i.e. `inscription-output.jpg`
7. Open the file and rejoice!

I made a video that goes over the thinking behind ordinals and I use this script to do a Proof of Inscription.

<iframe width="560" height="315" src="https://www.youtube.com/embed/s7O13il4-0Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>