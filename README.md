<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/clem9669/weblist">
    <img src="https://i.imgur.com/609h1jP.png" alt="Logo" width="400" height="200">
  </a>

  <h3 align="center">Weblist</h3>

  <p align="center">
    Wordlist for web fuzzing (FR & EN versions)
  </p>

> check out my hashcat rule project at: https://github.com/clem9669/hashcat-rule

> check out my wordlists project at: https://github.com/clem9669/wordlists

<!-- ABOUT THE PROJECT -->
## About The Project

While pentesting it is sometime hard to find a good worldlist to run with *dirb, wfuzz, gobuster, ffuf, feroxbuster and others*.

This project aims to give a good and complete wordlist for discovery (including French words). Put extensions accordingly to your webapp.

For extensions file, I recommand the [Raft file extensions](https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content).

The size of the wordlist is about:
```sh
wc -l decouverte.txt 
194611 decouverte.txt
```

### Built With
The main part of the list come from various place of internet but many thanks to :
* Dirbuster: directory-list-2.3-medium.txt
* Dirb lists: common + large
* Seclist > Discovery > Web-content: Raft
* French dictionnary
* API routes & scraps

The following projects could interest you:
  - https://github.com/nil0x42/duplicut
  - https://github.com/fuzzdb-project/fuzzdb
  - https://github.com/danielmiessler/SecLists
  - https://github.com/swisskyrepo/PayloadsAllTheThings
  - https://wordlists.assetnote.io/
  - https://github.com/clem9669/hashcat-rule


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/clem9669/weblist/issues) for a list of proposed features (and known issues).

## Recommended read

The following projects could interest you:

- https://tryhackme.com/room/ffuf
- https://www.acceis.fr/ffuf-advanced-tricks/

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


