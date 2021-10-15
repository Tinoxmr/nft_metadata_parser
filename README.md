# NFT metadata parser

### Purpose
Pulling metadata of nft collections for token rarity ranking.\
The script should return the complete metadata of an nft collection as a JSON file, formatted to be compatible with "rarity analyzer" softwares that can be found on GitHub, such as those developed for the [PunkScape Hackaton](https://github.com/punkscape/01-rarity-analyser-hackathon).

### Roadmap
1. Pull metadata from an IPFS nft directory with `requests` and save to raw json
2. Save to json with a correct formatting
3. Add support for any type of metadata directory (non-IPFS)
4. Implement "collection completenss" checks
5. Implement metadata pulling at reveal time
  
 ---
 
_NFTsummer.jpeg_
