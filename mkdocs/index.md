<p align="center" style="margin-bottom: 2em">
  <img src="https://raw.githubusercontent.com/4commerce-technologies-AG/midi-smtp-server/master/docs/img/midi-smtp-server-logo.png" alt="MidiSmtpServer Logo" width="50%"/>
</p>

<h1 align="center" style="margin-bottom: 0.3em">
  MidiSmtpServer
</h1>
<h2 align="center" style="margin-bottom: 0.3em">
  The highly customizable ruby SMTP-Service library
</h2>
<p align="center" style="margin-bottom: 3em">
-- Mail-Server, SMTP-Service, MTA, Email-Gateway & Router, Mail-Automation --
</p>


[MidiSmtpServer](https://github.com/4commerce-technologies-AG/midi-smtp-server) is the highly customizable ruby SMTP-Service library with builtin support for AUTH and SSL/STARTTLS, 8BITMIME and SMTPUTF8, IPv4 and IPv6 and additional features.

As a library it is mainly designed to be integrated into your projects as serving a SMTP-Server service. The lib will do nothing with your mail and you have to create your own event functions to handle and operate on incoming mails.

There is an endless field of application for SMTP-Services. You like to create your own SMTP-Server to receive messages and forward them plain or processed to services like Slack, Trello, Redmine, etc.


See ["Basic Usage"](basic_usage.md) to get yourself familiar with MidiSmtpServer's
capabilities.

MidiSmtpServer is an extremely flexible library and almost any aspect of SMTP communications can be handled by deriving its events and using its configuration options.

<br>