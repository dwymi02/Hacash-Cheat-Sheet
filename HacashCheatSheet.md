#Hacash Cheat Sheet
#####Author: Michael K. Dwyer
#####Date: Apr-13-2021
#####Version: 0.1.0

##Home: [Hacash Home page](https://hacash.org)
###White paper: [Hacash: A Crypto Currency System for Large-scale Payments and Real-time Settlement](https://hacash.org/file/hacash_white_paper_en.pdf)

##Important resources:
###These are Hacash resources that you will need to interface with the Hacash currency
* https://github.com/hacash/miner/blob/master/doc/software_release_log.md [Hacash Software Download]
* https://wallet.hacash.org [Online Wallet for Hacash]
* https://explorer.hacash.org [Hacash Explorer]
* http://hacash.ml [Hacash 3 Rewards Per Block Countdown]

##Public Hacash pools:
### Mining pools are Hacash nodes, where the constant race to solve Hacash blocks occur
### Note: mining pools differ from solo miners, in that mining pools reward miners with share rewards, without having to solve Hacash blocks. While solo miners are only rewarded when they solve the nonce for a Hacash block
* http://hacash.net [Fee 0.00%; Mining hacash.net:3339; Explorer hacash.net:3340]
* http://www.hacpool.com [Fee 0.10%; Mining 104.217.254.247:3339 -or- 163.123.181.77:3339; Explorer 104.217.254.247:3340 -or- 163.123.181.77:3340]

##Social media:
###A list of various social media platforms, where once you join, you will be able to ask questions and find resources to help you learn of the Hacash currency and its utility
* https://hacashtalk.com [A good resource for Hacash discussions]
* https://t.me/hacash [Hacash Community]
* https://t.me/HacashPool [HacashPool]
* Discord [See link at the left-hand bottom side of Hacash home page; copy link, then paste link into Discord]

##Important Hacash mining considerations:
###Before you start mining it will be necessary to ensure you have the requisite tools that will ensure your success mining Hacash
* As of the publication of this cheat sheet, Hacash is a CPU miner
* Presently, Hacash does not support GPU mining. Hacash may have support in the future. Use the important resources and social media resources to keep up to date with future Hacash developments
* Hacash is a Proof of Work (PoW), which means there is a worldwide competition to solve the mathematical puzzle, to be rewarded with shares of Hacash
* Hacash uses x16rs for PoW, comprised of 16 versions of SHA3. The hash algorithms used by x16rs are [Blake, BMW, Groestl, Jh, Keccak, Skein, Luffa, Cubehash, Shavite, Simd, Echo, Hamsi, Fugue, Shabal, Whirlpool, SHA512]
* Hacash is exclusively CPU intensive. Hacash is not reliant on memory. So when it comes to workstations one should focus on the number of cores and CPU speed. Simple rule, the more cores and the higher the CPU speed, the better will be your mining results.

##Creating your own Hacash wallet
###In this section you will be introduced to the Hacash wallet. The Hacash wallet are the keys, consisting of a public / private key that provides access to Hacash, a world leading alternative to the debt fiat currencies, run by the Global Central Banks
Many people are confused by the use of the public / private keys used by Hacash. To help you to understand the public / private key relationship used by Hacash, I will use your typical bank analogy.

Everyone understands how consumer banks operate.

First you need to open a bank account.

To open a bank account, you need to provide documentation proving your identity, where you live and source of income.

Once the bank decides to allow you to open an account, the bank will assign you a bank account number, a small number of checks, to allow you access to funds in your account and may optimally issue you a bank debit card.

The bank debit card and completed bank check are analogous to your Hacash public key. Your Hacash public key is like the bank debit card. Your Hacash public key represents what the public can see, just like your bank debit card or completed bank check. Your Hacash private key is analogous to your bank debit card pin number or your blank bank check. You would never give anyone your blank bank check and you certainly would never divulge your bank debit card pin number. Your Hacash private key allows the holder of the Hacash private key to spend, to pay bills, order services, buy the things you need, splurge on the things you want. Without your Hacash private key, you can do none of these things. It would be like forgetting your bank debit card pin number, if you don't have it and you don't have any of the Central Bank fiat currency in your pocket, you won't be able to buy anything.

For creating a Hacash wallet please refer to [Quick start](https://hacash.org/page/start_en.html)
There are two methods of creating a Hacash wallet, [Online Wallets](https://wallet.hacash.org/) or by downloading [Command-line Wallets](https://github.com/hacash/cmdwallet)

It is absolutely critical to understand that the public / private keys are inseparable. Once you decide to create a Hacash wallet, you must ensure that every possible means is employed to safely secure your Hacash wallet. If you lose either your public or private Hacash wallet keys, you will have lost access to your Hacash resources. While you can publicly advertise your Hacash public key to the world, your Hacash private key must be kept secret.


##Setting up to pool mine Hacash
###In this section we will be discussing how to set up your workstation to begin pool mining Hacash
###The software to run a Hacash pool miner either for UNIX/Linux or Windows can be accessed at [Join mining pool mining](https://hacash.org/page/start_en.html#poolworker) or from [Hacash Software Download link and Release log](https://github.com/hacash/miner/blob/master/doc/software_release_log.md).
###For the UNIX/Linux version use either [Download pool mining software](http://download.hacash.org:8080/miner_pool_worker_hacash_ubuntu64.zip) or [Hacash Software Download link and Release log ; 2. Miner pool worker:](http://download.hacash.org:8080/miner_pool_worker_hacash_ubuntu64.zip).
###For the Windows version use either [Download pool mining software](http://download.hacash.org:8080/miner_pool_worker_hacash_windows64.zip) or [Hacash Software Download link and Release log ; 2. Miner pool worker:](http://download.hacash.org:8080/miner_pool_worker_hacash_windows64.zip)


Once you unpack the zip archives you will see two files, an executable, with the following naming convention:
####hacash_miner_pool_worker_YYYY_MM_DD_VV, where YYYY is the year, MM is the month, DD is the day and VV is the release version

####Note: Windows executables will have a file extension of [.exe], while UNIX/Linux avoids this convention.
####The other file is the Hacash pool miner configuration file with the name poolworker.config.ini
####Note: If you rename or delete the file poolworker.config.ini and begin mining by running the pool worker executable, default values will be taken, which may not be suitable for your machines configuration. When starting the Hacash pool worker, carefully examine the console log to ensure that what is displayed on the console screen matches your configuration settings.

####The poolworker.config.ini configuration file consists of three keywords, they are [pool], [rewards] and [supervene]
####The [pool] keyword specifies the IP address or URL and port number, where you wish to pool mine Hacash. Examples of existing public Hacash pools would be [http://www.hacpool.com] or [http://hacash.net]. You can specify either the IP address or the URL with the port number the site uses for incoming connections.
####The [rewards] keyword is your Hacash public wallet address key.
####The [supervene] keyword represents the number of cores your workstation has installed. So, for example, your workstation has 8 cores, you would set this keyword to the number of cores on your workstation.
####Following is an example of the file poolworker.config.ini, which at the time of this writing are the contents of the original pool worker configuration file:

    pool = 182.92.163.225:3339
    rewards = 1AVRuFXNFi3rdMrPH4hdqSgFrEBnWisWaS
    supervene = 8

####The [pool] keyword directs the Hacash pool worker to access the public Hacash pool using IP address [182.92.163.225], the pool server uses port number 3339 to listen for new connections
####The [rewards] keyword specifies the Hacash public wallet key. Hacash shares are accumulated by the Hacash pool server and are distributed to your Hacash public wallet key.
####Once you commence Hacash mining operations, I would recommend using your favorite web browser to track progress of your workers by specifying the [pool] IP address using port number [:3340].

So, the following is how you would enter this into your browser:

    https://182.92.163.225:3340

The results will appear as follows (formatted to fit):

    FeeRatio: 10.00 %, Addr: 1BGxnkVmNQECbvBYbvdquFQZBLgBpVLkYr

    Port: 3339

    TotalClients: 9

				Address						Clients	  PeriodPowWorth  FindBlocks/Coins	CompleteRewards	DeservedRewards	UnconfirmedRewards
    1	1L5xEapTvXjLMmLtAEGNRMhtBgZ17qgZbA	   6	679905489499910762	24/48		ㄜ4,241,412,050:240			ㄜ0:240			   ㄜ0:240
    2	166mrvPkBnBqq232EA1xdwwt8Gc5eDWXyA	   2	 70700324540875497	 0/0					ㄜ0:240	ㄜ1,087,252:240		  ㄜ57,820:240
    3	1JTkcrsPYyJu8uDNHub7jFuaFoXJWJNdfU	   1	110444812137922294	 4/8		  ㄜ690,418,374:240			ㄜ0:240	  ㄜ12,648,687:240
    4	1EQfBd4MpA8usQNUgdUaHaDyVPjxJNtr4t	   0					 0	 0/0					ㄜ0:240			ㄜ0:240			   ㄜ0:240
    5	1Miy6qEWuSYydaFY5BiCBuwpA8Z6aQLaMv	   0	   430551781343229	 0/0					ㄜ0:240			ㄜ0:240			   ㄜ0:240
