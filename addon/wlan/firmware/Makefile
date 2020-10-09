#
# Makefile
#

BASEURL = https://github.com/sarins/firmware-nonfree/raw/master

firmware: clean
	wget -q -O LICENCE.broadcom_bcm43xx $(BASEURL)/LICENCE.broadcom_bcm43xx
	wget -q -O brcmfmac43430-sdio.bin $(BASEURL)/brcm/brcmfmac43430-sdio.bin
	wget -q -O brcmfmac43430-sdio.txt $(BASEURL)/brcm/brcmfmac43430-sdio.txt
	wget -q -O brcmfmac43455-sdio.bin $(BASEURL)/brcm/brcmfmac43455-sdio.bin
	wget -q -O brcmfmac43455-sdio.txt $(BASEURL)/brcm/brcmfmac43455-sdio.txt
	wget -q -O brcmfmac43455-sdio.clm_blob $(BASEURL)/brcm/brcmfmac43455-sdio.clm_blob

clean:
	rm -f *.bin *.txt *.clm_blob LICENCE*
