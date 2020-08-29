# Modified Bustabit Script

When employed correctly, this strategy seems to earn profits, but it's entirely dependent on the size of your bankroll and profit goals.  I plan to run further simulation tests with this.  Reccomendations below.

### Disclaimer
I (Adam Gasiewski) am not responsible for any loss that one may incur using this script.  It is impossible to turn an EV- game to EV+.  Please gamble responsibly and understand how this program works.


## Strategy
This script employs the martingale strategy.
I modified an existing martingale script to automatically end itself once a specified profit has been made. This helps reduce the amount of times you wipe your bankroll since you don't let the script run endlessly.

For example, if you have 1000 bits and want the script to end once a 100 bit profit has been attained, you would put 100 in the "profit to end script" field.

I will update this once I run more simulations but a 2:1 ratio (Starting Balance: Profit Goal) seems to be effective.



Author
: Adam Gasiewski


*[martingale strategy]: Doubling your bet after every loss until you win in order to recoup losses.
