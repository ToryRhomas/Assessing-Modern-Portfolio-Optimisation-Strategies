In this project, 5 peers and I attempted to assess the effectiveness of the strategies involved in Modern Portfolio theory. Much of this work involved using algorithmic methods to simulate these methods on historical data for later behaviour assessment.

Grade Earned: High Distinction

Throughout the first two years of a Bachelor of Data Science (Advanced) at Monash students complete 4 data-driven group projects on their choice of provided topics. This was my third of these 4 projects and was completed in Year 2 Semester 1 of my degree.

The main skill I demonstrated in this project was alogrithmic thinking and data simulation. We started the project with clean and extensive price data and the most intuitive way to start assessing the effectiveness of different startegies was to simulate these strategies using the data. This process required both fluency in python and a strong algorithmic skills as to make our simulations mirror reality.

Throughout the project several distinct types of portfolio weighting and stock choosing strategies
were considered. In experimenting with the stocks and weights, 7 strategies were shortlisted,
each with a different combination of choice of stocks and choice of weights. The first of these
strategies was to purely test the effectiveness of weight optimisation and consisted of choosing
stocks at random and then adjusting their weights each year to maximise Sharpe Ratio. The
next three strategies chose stocks by maximising expected return while using a variety of
methods to adjust the weights of stocks. Similarly, the third strategy involved choosing stocks to
maximise Sharpe ratio of the portfolio and each of the same variety of weight adjustment
methods were tested. These weight adjustment methods were weighting the stocks equally and
letting it run, adjusting weights every 5 years to maximise the portfolio’s Sharpe ratio and
adjusting weights every 5 years to minimise the portfolio’s variance. Each of these strategies
were then compared to a baseline strategy in which stocks were chosen at random and given
equal weights. Ideally, the tested strategies will outperform this baseline in KPI’s such as return
and Sharpe Ratio by a significant amount thus implying its effectiveness and worth.
Here is a key question to this project: What is a “better” stock portfolio, or, more precisely, what
is counted as a “good” stock portfolio? This question was explored through the different
strategies and the comparisons between those strategies, however, a clear goal needed to be
specified. The chosen goal was minimising risk and maximising return. A straightforward way to
analyse this metric of risk and return is by using a formula called the Sharpe ratio. This is the
ratio of return over risk and produces a metric that can easily be analysed to compare
strategies. In addition, returns were also taken into consideration, due to the end goal of
investing in stocks being to earn money. In summary it was defined that a good portfolio was
one with a high return value with a high Sharpe ratio.
Upon creating the baseline strategy, it was found that the strategy produced unstable results.
Not only was the overall strategy producing inconsistent a large variety of results, meaning that
it can return an extremely low amount, but also an extremely high amount, each individual
portfolio produced was also unstable. This was then visible through the strategies relatively low
average Sharpe Ratio of 0.81.
The next strategy (strategy 1 in the report) then introduced dynamic trading principles such as
adjusting weight yearly to maximise the portfolio’s Sharpe ratio. Using this strategy led to a
more table set of portfolios by firstly, generating a smaller range of portfolios and improving
average Sharpe Ratio to be 0.93. This meant that the strategy behaved more predictably in a
holistic sense, but also individual portfolios behaved more predictably thus incurring less risk.
Furthermore, as the strategy had a similar return it was an effective method of optimising
portfolios and confirmed that weight adjustment was a worthwhile practice for trading.
After this the rest of the trading strategies were all compared to not only find the best way to
choose stocks to include in the portfolio but to also find the best way to weight the stocks in the
portfolio. For these, there were 3 weight optimization methods that were tested and two stock
choosing methods as previously mentioned. All portfolio’s performed far better than the
previously discussed strategies thus implying the conclusion that optimal stock choice was more
important than weight adjustment when its portfolio optimisation. The most effective of these
strategies and the ones that would later be recommended to the audience were adjusting
weights to maximize Sharpe Ratio while choosing stocks by maximizing the portfolio’s Sharpe
Ratio and adjusting weights to minimize volatility while choosing stocks by maximizing the
portfolio Sharpe Ratio. The former of these strategies produced an impressive Sharpe Ratio of
1.992 and the latter demonstrated remarkably stable growth.
Ultimately, these realisations led us to the conclusion that our hypothesis was false and that
these strategies were capable of effectively producing optimised portfolios that performed well in
portfolio KPI’s. Namely, the strategy of adjusting weights to maximize Sharpe Ratio while
choosing stocks by maximizing the portfolio’s Sharpe Ratio had such strong performance that
despite its difficult implementation, it would be a worthwhile strategy to use in the real world.
Like most things the project was not without its flaws. Comparisons with ETF’s and questionable
figures brought about the realisation that although the analysis was done correctly, some biases
in the data that was used meant that investigation was not adjacent to the real world. Examples
of this included data being comprised of already high performing stocks, strategies
unintentionally drawing on future events and ignoring costs such as taxes and trading fees.
Nonetheless, all comparisons within the project, barring comparison to an ETF, still had merit as
the strategies were still tested on a level playing field. Furthermore, these issues could act as
points to discuss in further projects in which more data could be used, and more factors could
be incorporated. Moreover, findings of this project could act as a framework to further test the
altering the parameters of portfolios such as testing readjustment intervals or portfolio size.
