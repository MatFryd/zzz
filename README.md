# zzz

Cards are serialized 0..51, with 0 being 2 of clubs ('2c') and 51 being 'Ah'.

Suits are serialized [c, d, s, h].

The rank of ace cards is considered 14.

A serial of 52 represents an unknown card ('?').

# Conversions:
## serial == 13 * suit + (rank - 2)
## suit == serial ~/ 13
## rank == serial % 13 + 2
