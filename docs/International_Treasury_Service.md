Client: Richard Watts, [BigPay](BigPay "wikilink")
<richard@bigpayme.com> or James Hinshelwood

Many companies have to work across currencies. BigPay operates in both
Malaysia and Singapore, and has to use an external service provider to
move money between the two. It would be more efficient to do this
themselves, managing reserves of both currencies (MYR and SGD), setting
an exchange rate, and executing and settling transfers taking at least a
day to complete. Your job is to design a software system capable of
managing and visualising these reserves. It should take a feed of the
buy and sell rates available from partners at various distances in time
(1 day, 7 day, 30 day) and export an API allowing users to give a target
currency and amount and receive a price (and then confirm the transfer).
As far as possible, the system should achieve optimal revenue. You will
need to write a simulator for exchange rates and for customer behaviour.