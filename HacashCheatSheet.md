# Hacash Cheat Sheet

##### Author: Michael K. Dwyer

##### Date: Apr-13-2021

##### Last updated: Apr-14-2021

##### Version: 0.1.4

## Home: [Hacash Home page](https://hacash.org)

### White paper: [Hacash: A Crypto Currency System for Large-scale Payments and Real-time Settlement](https://hacash.org/file/hacash_white_paper_en.pdf)

## Important resources:

### These are Hacash resources that you will need to interface with the Hacash currency
* https://github.com/hacash/miner/blob/master/doc/software_release_log.md [Hacash Software Download]
* https://wallet.hacash.org [Online Wallet for Hacash]
* https://explorer.hacash.org [Hacash Explorer]
* http://hacash.ml [Hacash 3 Rewards Per Block Countdown]

## Public Hacash pools:

### Mining pools are Hacash nodes, where the constant race to solve Hacash blocks occur

### Note: mining pools differ from solo miners, in that mining pools reward miners with share rewards, without having to solve Hacash blocks. While solo miners are only rewarded when they solve the nonce for a Hacash block
* http://hacash.net [Fee 0.00%; Mining hacash.net:3339; Explorer hacash.net:3340]
* http://www.hacpool.com [Fee 0.10%; Mining 104.217.254.247:3339 -or- 163.123.181.77:3339; Explorer 104.217.254.247:3340 -or- 163.123.181.77:3340]

## Social media:

### A list of various social media platforms, where once you join, you will be able to ask questions and find resources to help you learn of the Hacash currency and its utility
* hashtalk.com: [A good resource for Hacash discussions](https://hacashtalk.com)
* Telegram group: [Hacash Community](https://t.me/hacash)
* Telegram group: [HacashPool](https://t.me/HacashPool)
* Discord: [See link at the left-hand bottom side of Hacash home page; copy link, then paste link into Discord]
* Twitter accounts: @HacashWorld @HacashPool
* YouTube: [Hacash Mining Guide | Solo & Join Pool | Windows | CPU Mining](https://www.youtube.com/watch?v=oebtvRWKj9c)

## Important Hacash mining considerations:

### Before you start mining it will be necessary to ensure you have the requisite tools that will ensure your success mining Hacash
* As of the publication of this cheat sheet, Hacash is a CPU miner
* Presently, Hacash does not support GPU mining. Hacash may have support in the future. Use the important resources and social media resources to keep up to date with future Hacash developments
* Hacash is a Proof of Work (PoW), which means there is a worldwide competition to solve the mathematical puzzle, to be rewarded with shares of Hacash
* Hacash uses x16rs for PoW, comprised of 16 versions of SHA3. The hash algorithms used by x16rs are [Blake, BMW, Groestl, Jh, Keccak, Skein, Luffa, Cubehash, Shavite, Simd, Echo, Hamsi, Fugue, Shabal, Whirlpool, SHA512]
* Hacash is exclusively CPU intensive. Hacash is not reliant on memory. So when it comes to workstations one should focus on the number of cores and CPU speed. Simple rule, the more cores and the higher the CPU speed, the better will be your mining results.

## Creating your own Hacash wallet

### In this section you will be introduced to the Hacash wallet. The Hacash wallet are the keys, consisting of a public / private key that provides access to Hacash, a world leading alternative to the debt fiat currencies, run by the Global Central Banks
Many people are confused by the use of the public / private keys used by Hacash. To help you to understand the public / private key relationship used by Hacash, I will use your typical bank analogy.

Everyone understands how consumer banks operate.

First you need to open a bank account.

To open a bank account, you need to provide documentation proving your identity, where you live and source of income.

Once the bank decides to allow you to open an account, the bank will assign you a bank account number, a small number of checks, to allow you access to funds in your account and may optimally issue you a bank debit card.

The bank debit card and completed bank check are analogous to your Hacash public key. Your Hacash public key is like the bank debit card. Your Hacash public key represents what the public can see, just like your bank debit card or completed bank check. Your Hacash private key is analogous to your bank debit card pin number or your blank bank check. You would never give anyone your blank bank check and you certainly would never divulge your bank debit card pin number. Your Hacash private key allows the holder of the Hacash private key to spend, to pay bills, order services, buy the things you need, splurge on the things you want. Without your Hacash private key, you can do none of these things. It would be like forgetting your bank debit card pin number, if you don't have it and you don't have any of the Central Bank fiat currency in your pocket, you won't be able to buy anything.

For creating a Hacash wallet please refer to [Quick start](https://hacash.org/page/start_en.html)
There are two methods of creating a Hacash wallet, [Online Wallets](https://wallet.hacash.org/) or by downloading [Command-line Wallets](https://github.com/hacash/cmdwallet)

It is absolutely critical to understand that the public / private keys are inseparable. Once you decide to create a Hacash wallet, you must ensure that every possible means is employed to safely secure your Hacash wallet. If you lose either your public or private Hacash wallet keys, you will have lost access to your Hacash resources. While you can publicly advertise your Hacash public key to the world, your Hacash private key must be kept secret.


## Setting up to pool mine Hacash

### In this section we will be discussing how to set up your workstation to begin pool mining Hacash

### Before beginning a discussion on configuring a Hacash pool miner, one needs to understand the benefits of pool mining as opposed to Hacash solo mining, which we will also outline in this Hacash Cheat Sheet. Generally, new miners dabble with solo mining, only to quickly become frustrated over results, then give up incorrectly believing that mining is not profitable. Firstly, one needs to understand when you should solo mine and when you need to pool mine. The Hacash miner application provides useful information, once you know what to look for. Once your Hacash miner is running, take a good look at console log. An example of the console log is provided:

    do mining height:‹231855›, cbmn:54... upload hash: 231854, 000000963c112af958095885..., time: 244s, hashrate: 12.566TH/s ok.

### Notice the value for [hashrate:], the value reads [12.566TH/s]. This is what you want to look for. Possible values, from lowest to highest are [GH/s], [TH/s], [PH/s]. If your miner is reporting a hash rate in [GH/s] or low [TH/s], then you should be pool mining. On the other hand, if your miner is reporting hash rates in the high [TH/s] or even [PH/s], then you should consider solo mining. That having been said, even if you have extremely high hash rates, you can still pool mine. That is a decision each individual must make for themselves.

### Now we will quickly go over some of the differences between Hacash pool mining and Hacash solo mining. We will start with Hacash solo mining. When one Hacash solo mines the only reward is when the Hacash miner solves the nonce for the Hacash blockchain. Which is the primary reason why individuals with moderately powered computers must pool mine. In pool mining, there are two methods for receiving Hacash rewards. The most lucrative is solving the nonce for the Hacash blockchain, the other being rewarded with Hacash shares for contributing to the integrity and security of the Hacash blockchain. Once a pool miner accrues enough Hacash rewards, the pool will send to your public Hacash public key wallet, your accrued Hacash shares. Over time, one can accumulate a vast amount of Hacash.

### Another distinguishing characteristic between Hacash pools and Hacash nodes is every Hacash pool must have three ports open to the world, these ports are port # 3338 for basic nodes, port # 3339, which connects the pool to Hacash client applications, viz., the executable we run to perform mining operations and port # 3340, which allows users to monitor their Hacash clients, along with other clients also connected to the pool.

### The software to run a Hacash pool miner either for UNIX/Linux or Windows can be accessed at [Join mining pool mining](https://hacash.org/page/start_en.html#poolworker) or from [Hacash Software Download link and Release log](https://github.com/hacash/miner/blob/master/doc/software_release_log.md).

### For the UNIX/Linux version use either [Download pool mining software](http://download.hacash.org:8080/miner_pool_worker_hacash_ubuntu64.zip) or [Hacash Software Download link and Release log ; 2. Miner pool worker:](http://download.hacash.org:8080/miner_pool_worker_hacash_ubuntu64.zip).

### For the Windows version use either [Download pool mining software](http://download.hacash.org:8080/miner_pool_worker_hacash_windows64.zip) or [Hacash Software Download link and Release log ; 2. Miner pool worker:](http://download.hacash.org:8080/miner_pool_worker_hacash_windows64.zip)


Once you unpack the zip archives you will see two files, an executable, with the following naming convention:
#### hacash_miner_pool_worker_YYYY_MM_DD_VV, where YYYY is the year, MM is the month, DD is the day and VV is the release version

#### Note: Windows executables will have a file extension of [.exe], while UNIX/Linux avoids this convention.

#### The other file is the Hacash pool miner configuration file with the name poolworker.config.ini

#### Note: If you rename or delete the file poolworker.config.ini and begin mining by running the pool worker executable, default values will be taken, which may not be suitable for your machines configuration. When starting the Hacash pool worker, carefully examine the console log to ensure that what is displayed on the console screen matches your configuration settings.

#### The poolworker.config.ini configuration file consists of three keywords, they are [pool], [rewards] and [supervene]

#### The [pool] keyword specifies the IP address or URL and port number, where you wish to pool mine Hacash. Examples of existing public Hacash pools would be [http://www.hacpool.com] or [http://hacash.net]. You can specify either the IP address or the URL with the port number the site uses for incoming connections.

#### The [rewards] keyword is your Hacash public wallet address key.

#### The [supervene] keyword represents the number of cores your workstation has installed. So, for example, your workstation has 8 cores, you would set this keyword to the number of cores on your workstation.

#### Following is an example of the file poolworker.config.ini, which at the time of this writing are the contents of the original pool worker configuration file:

    pool = 182.92.163.225:3339
    rewards = 1AVRuFXNFi3rdMrPH4hdqSgFrEBnWisWaS
    supervene = 8

#### The [pool] keyword directs the Hacash pool worker to access the public Hacash pool using IP address [182.92.163.225], the pool server uses port number 3339 to listen for new connections

#### The [rewards] keyword specifies the Hacash public wallet key. Hacash shares are accumulated by the Hacash pool server and are distributed to your Hacash public wallet key.

#### Once you commence Hacash mining operations, I would recommend using your favorite web browser to track progress of your workers by specifying the [pool] IP address using port number [:3340].

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



## Setting up to solo mine Hacash
### In this section we will be discussing how to set up your workstation to begin solo mining Hacash
### The software to run a Hacash solo miner either for UNIX/Linux or Windows can be accessed at [Full node mining](https://hacash.org/page/start_en.html#minernode) or from [Hacash Software Download link and Release log](https://github.com/hacash/miner/blob/master/doc/software_release_log.md).

### For the UNIX/Linux version use either [Download mining node software](http://download.hacash.org:8080/miner_node_hacash_ubuntu64.zip) or [Hacash Software Download link and Release log ; 1. Hacash full node:](http://download.hacash.org:8080/miner_node_hacash_ubuntu64.zip).

###For the Windows version use either [Download mining node software](http://download.hacash.org:8080/miner_node_hacash_windows64.zip) or [Hacash Software Download link and Release log ; 1. Hacash full node:](http://download.hacash.org:8080/miner_node_hacash_windows64.zip)


Once you unpack the zip archives you will see two files, an executable, with the following naming convention:
#### hacash_miner_node_hacash_YYYY_MM_DD_VV, where YYYY is the year, MM is the month, DD is the day and VV is the release version

#### Note: Windows executables will have a file extension of [.exe], while UNIX/Linux avoids this convention.

#### The other file is the Hacash pool miner configuration file with the name hacash.config.ini

#### Note: If you rename or delete the file hacash.config.ini and begin mining by running the pool worker executable, default values will be taken, which may not be suitable for your machines configuration. When starting the Hacash solo worker, carefully examine the console log to ensure that what is displayed on the console screen matches your configuration settings.

#### The hacash.config.ini configuration file is divided into six sections, they are [p2p], [miner], [minerpool], [diamondminer], [service] and [btcmovecheck]

#### The following sections will not be discussed here. No changes should be made to any of the sections listed. Changing values for these keywords could result in unpredictable mining behavior. To reiterate, when solo mining, make no changes to the following sections in the file hacash.config.ini. The sections to be ignored are [p2p], [minerpool], [diamondminer], [service] and [btcmovecheck]

#### The section to be updated for solo mining is [miner], the keywords, within the [miner] section that we will look at are [enable], [supervene], [rewards] and [message].

#### When you look at the section [miner], you will notice that there is a [;] preceding the [enable] keyword. Anything after the [;] are treated as comments, meaning that the Hacash solo miner will use the default for this keyword. If no changes were to be made, when the Hacash solo miner is started, no mining threads would be started. This is not the behavior we desire, we want to solve as many Hacash nonce's as possible. To facilitate this we need to remove the [;] from the [enable] keyword. Once the [;] has been removed from the [enable] keyword, we need to set the next Hacash solo miner keyword.

#### The [rewards] keyword is your Hacash public wallet address key.

#### The [supervene] keyword represents the number of cores your workstation has installed. So, for example, your workstation has 8 cores, you would set this keyword to the number of cores on your workstation.

#### The [rewards] keyword is your Hacash public wallet address key.

#### The [message] keyword represents the name of your solo miner. When assigning a name, long names will get truncated, when viewed publicly.

#### Because the hacash.config.ini contains a number of lines, we will display the contents of a hacash.config.ini ready for use as a solo miner, which would be as follows (white space lines have been omitted):

    ;;; hacash node config
    [p2p]
    ;name = hnode_test1
    ;boot_node_fast_sync = true
    listen_port = 3337
    boot_nodes = 182.92.163.225:3337,47.244.26.14:3337,38.17.55.47:3337
    [miner]
    enable = true
    supervene = 8
    rewards = 1AVRuFXNFi3rdMrPH4hdqSgFrEBnWisWaS
    message = MySoloPoolWorker
    [minerpool]
    ;enable = true
    data_dir = hacash_minerpool_data
    console_http_port = 3340
    listen_port = 3339
    max_connect = 200
    fee_percentage = 0.05
    rewards_password = 123456
    [diamondminer]
    ;enable = true
    supervene = 6
    fee_amount = ㄜ1:247
    fee_password = abc123456
    rewards = 1AVRuFXNFi3rdMrPH4hdqSgFrEBnWisWaS
    continued = false
    autobid = true
    autobid_fee_max = ㄜ10:248
    autobid_fee_margin = ㄜ2:247
    [service]
    ;enable = true
    ;deprecated_http_port = 3338
    rpc_listen_port = 8083
    [btcmovecheck]
    enable = true
    logs_url = http://127.0.0.1:3366/btcmovelogs


## Hacash tutorials
### This section provides links to Hacash approved tutorials

The following pdf, a step by step guide on how to get ready to mine Hacash [HacashPool Step by Step Setup Guide](https://hacashpool.com/HacashPool-Wallet-Mining-Node-Setup-Guide.pdf)

The following video provides a step by step guide on how to get ready to mine Hacash [HacashPool Mining Setup Tutorial](https://vimeo.com/449931688)

The following YouTube video provides a step by step guide on how to get ready to mine Hacash [Hacash Mining Guide | Solo & Join Pool | Windows | CPU Mining](https://www.youtube.com/watch?v=oebtvRWKj9c)


## Hacash resources:
### This section provides links to Hacash resources

Forums: [Mining the world's first PoW-based NFT by CPU](https://bitcointalk.org/index.php?topic=5266623.0)

Article: [What is Hacash?](https://kenyou.medium.com/what-is-hacash-52bcd7b438ea)

Article: [Hacash : An Open source Encryption Project with “Monetary” as its Core Target](https://vaibhavc.medium.com/hacash-an-open-source-encryption-project-with-monetary-as-its-core-target-c11c03188f1d)

Web page: [Current Hacash supply](https://ha.cash/totalsupply)

Web page: [HACASH 3 REWARDS PER BLOCK COUNTDOWN](http://hacash.ml)

Web page: [Unformatted list of Hacash nodes](http://hacash.net:3338)


## Donations to Hacash:
### If you found value in this Hacash Cheat Sheet and would like to support our efforts to advance Hacash, please consider helping by donating using the Hacash.org public key wallet: [1KSXVdjR9YJQ92fWqJRDuoJtci8TaDeK8q]
