# Lazy Iterators

To illustrate the application of lazy iterators, the dataset `nyc_parking_tickets_extract-1.csv` is considered. Module collections offer Counter method that can be used to count the items of interest in an instance over the range of data.

`yield from` is a generator used to generate the data, and namedtuple `ParkingTickets` is used to denote observations from the rows of data.

`get_data()` yields data from a single row from the dataset each time it is called for, and `gen_tkts` makes a namedtuple() out of the generated data from `get_data()`.

`carmake_data()` gives the output of Counter() on sequences of data generated from generator.



