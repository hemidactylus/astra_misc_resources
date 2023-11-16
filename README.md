# Astra Resources (steo)

## Cassandra warning removal

How to remove (most of) the scary, harmless warnings when connecting to
Astra with the Cassandra drivers (and by extension CassIO).

This is a Colab problem (Colab has wide logging filters by default).

[Try in Colab](https://colab.research.google.com/github/hemidactylus/astra_misc_resources/blob/main/cassandra_logging_suppression.ipynb)

_Note:_ the remaining `USE_BETA flag` error will be staying for very long probably (it's from server, so the driver carry it to the user as is, as it should).
The best thing IMO here is to warn the user not to worry. I know it's not ideal, but other solutions seem contrived and wrong to me.
