


# Dev2 Branch

The log file just shows some startups/shutdowns of Apache workers. In your Apache configuration, you can set how many workers (aka threads) Apache may use. On a regular setup, Apache can be started several times. Especially when your server is busy (e.g. there are many visitors on one of your vhosts), it's not strange to see 20 (or more) Apache processes running. There is nothing to worry about, they're just informational.


