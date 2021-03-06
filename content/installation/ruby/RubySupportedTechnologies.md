<!-- 
title: "Supported Technologies"
description: "List of supported technologies"
tags: "installation Ruby on Rails agent frameworks support troubleshooting gem"
-->

The Ruby agent supports Ruby language version 2.1.x and above. Framework support is currently for Ruby on Rails versions 3.x and above and Sinatra 2.x and above. The Ruby agent is a standard Rack middleware; it may work in other Rack-based web frameworks like Sinatra. 

## Database Support

The Ruby Agent has SQL Injection modules for MySQL (`mysql2` gem), SQLite3 and PostgreSQL (`pg` gem). The Ruby Agent also has NoSQL Injection modules for MongoDB (`mongoid` gem).

## OS Support

Agent testing is done on **64-bit OSX** and **64-bit Linux**. The agent has no *C* dependencies, and may work in other operating system environments. However, the associated service depends on Nokogiri and EventMachine, and may have trouble compiling under non-supported operating systems.


