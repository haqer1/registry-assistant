# registry-assistant
Facilitates Windows Registry interactions with some advantages over regedit.exe... 

## Supported locales:
Crimean Tatar, English, French, Turkish

## UI screenshots (in various locales):
![Search tab (in French)](docs/include/img/intro/rechercher.fr.png)
![Explore tab (in Turkish)](docs/include/img/intro/browsing.tr.png)
![About tab (in English)](docs/include/img/intro/about.en.png)
![(Interrupted) search results (in Crimean Turkish)](docs/include/img/intro/search_results.crh.png)

## Troubleshooting
### If during execution you see the following error message:
	`The code execution cannot proceed because VCRUNTIME140.dll was not found. Reinstalling the program may fix this problem.`
	You need to install a Visual C++ (2015-2019) Runtime Redistributable to run Registry Assistant:
		1. Download 1 of the following files (based on your device's architecture)
			(from the links below or equivalent links at 
			[support.microsoft.com](https://support.microsoft.com/en-gb/help/2977003/the-latest-supported-visual-c-downloads):
				- [vc_redist.x64.exe](https://aka.ms/vs/16/release/vc_redist.x64.exe)
				- [vc_redist.x86.exe](https://aka.ms/vs/16/release/vc_redist.x86.exe)
				- [VC_redist.arm64.exe](https://aka.ms/vs/16/release/VC_redist.arm64.exe)
		2. Run it to install the Visual C++ 2015-2019 Redistributable (which will be usable by other applications afterwards as well).
		3. Once you see a window like the following, you can run Registry Assistant:
		![Alt text](docs/include/img/troubleshooting/redistributable-installed.png?raw=true "Redistributable installed")

