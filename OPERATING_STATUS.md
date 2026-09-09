# Operating status

Scheduled trading is paused. The corrected cached-data replay returned a 1.058 profit factor, 8.02% CAGR, and 40.99% maximum drawdown across 1,210 trades. That drawdown and the small margin above break-even do not support unattended scheduling.

This strategy also trades QQQ in the same Alpaca paper account as the 5-minute ORB, CVD, and Orochi bots. Those processes cannot safely own and close separate QQQ positions in one netted account. Manual dispatch remains available for isolated testing.
