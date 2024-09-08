# Proxmox-RAID
This is a repo to document Proxmox RAID

## Command Output Reference
Note:
All of the outputs are in Command_Outputs/
The piping to the file is not included in the reference command.


| Command Ran | Description | File |
|:------------| :---------: | ---: |
| lspci -vvv -s 03:00.0 | This get the PCI information for the RAID Card | [lspci.txt](Command_Outputs/lspci.txt) |
| megasasctl -vest -B | The diagnostic report for the sas drives | [megasasctl.09-08-2024_04-41.log](Command_Outputs/megasasctl.09-08-2024_04-41.log) |


## PDF File Reference
| File | Description |
| :--: | :---------- |
| [dell-perc-h310-spec-sheet.pdf](PDFs/dell-perc-h310-spec-sheet.pdf) | This is the RAID car  d Spec sheet |
| [MegaCLI-user_guide.pdf](PDFs/MegaCLI-user_guide.pdf) | The command megacli user guide |