# Factura



```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<rDE xmlns="http://ekuatia.set.gov.py/sifen/xsd" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://ekuatia.set.gov.py/sifen/xsd siRecepDE_v150.xsd">
    <dVerFor>150</dVerFor>
    <DE Id="12341234123412341234123412341234123412341234">
        <dDVId>5</dDVId>
        <dFecFirma>2024-01-02T10:36:10</dFecFirma>
        <dSisFact>1</dSisFact>
        <gOpeDE>
            <iTipEmi>1</iTipEmi>
            <dDesTipEmi>Normal</dDesTipEmi>
            <dCodSeg>056356826</dCodSeg>
        </gOpeDE>
        <gTimb>
            <iTiDE>1</iTiDE>
            <dDesTiDE>Factura electrónica</dDesTiDE>
            <dNumTim>123456789</dNumTim>
            <dEst>001</dEst>
            <dPunExp>001</dPunExp>
            <dNumDoc>0000017</dNumDoc>
            <dFeIniT>2023-10-06</dFeIniT>
        </gTimb>
        <gDatGralOpe>
            <dFeEmiDE>2024-01-02T09:20:00</dFeEmiDE>
            <gOpeCom>
                <iTipTra>1</iTipTra>
                <dDesTipTra>Venta de mercadería</dDesTipTra>
                <iTImp>1</iTImp>
                <dDesTImp>IVA</dDesTImp>
                <cMoneOpe>PYG</cMoneOpe>
                <dDesMoneOpe>Guarani</dDesMoneOpe>
            </gOpeCom>
            <gEmis>
                <dRucEm>80012345</dRucEm>
                <dDVEmi>6</dDVEmi>
                <iTipCont>2</iTipCont>
                <cTipReg>8</cTipReg>
                <dNomEmi>NOMBRE DE LA ENTIDAD</dNomEmi>
                <dNomFanEmi>NOMBRE DE LA ENTIDAD</dNomFanEmi>
                <dDirEmi>DIRECCIÓN 1</dDirEmi>
                <dNumCas>NUMERACIÓN</dNumCas>
                <dCompDir1>COMPLEMENTO DIRECCIÓN 1</dCompDir1>
                <cDepEmi>1</cDepEmi>
                <dDesDepEmi>CAPITAL</dDesDepEmi>
                <cDisEmi>1</cDisEmi>
                <dDesDisEmi>ASUNCION (DISTRITO)</dDesDisEmi>
                <cCiuEmi>1</cCiuEmi>
                <dDesCiuEmi>ASUNCION (DISTRITO)</dDesCiuEmi>
                <dTelEmi>0981123456</dTelEmi>
                <dEmailE>correo@entidad.com.py</dEmailE>
                <dDenSuc>CASA CENTRAL</dDenSuc>
                <gActEco>
                    <cActEco>47591</cActEco>
                    <dDesActEco>COMERCIO AL POR MENOR DE ELECTRODOMÉSTICOS Y ACCESORIOS</dDesActEco>
                </gActEco>
            </gEmis>
            <gDatRec>
                <iNatRec>2</iNatRec>
                <iTiOpe>2</iTiOpe>
                <cPaisRec>PRY</cPaisRec>
                <dDesPaisRe>Paraguay</dDesPaisRe>
                <iTipIDRec>1</iTipIDRec>
                <dDTipIDRec>Cédula paraguaya</dDTipIDRec>
                <dNumIDRec>1234656</dNumIDRec>
                <dNomRec>Camila Gómez</dNomRec>
                <dEmailRec>correo.cliente@hotmail.com</dEmailRec>
            </gDatRec>
        </gDatGralOpe>
        <gDtipDE>
            <gCamFE>
                <iIndPres>1</iIndPres>
                <dDesIndPres>Operación presencial</dDesIndPres>
            </gCamFE>
            <gCamCond>
                <iCondOpe>1</iCondOpe>
                <dDCondOpe>Contado</dDCondOpe>
                <gPaConEIni>
                    <iTiPago>1</iTiPago>
                    <dDesTiPag>Efectivo</dDesTiPag>
                    <dMonTiPag>5000</dMonTiPag>
                    <cMoneTiPag>PYG</cMoneTiPag>
                    <dDMoneTiPag>Guarani</dDMoneTiPag>
                </gPaConEIni>
            </gCamCond>
            <gCamItem>
                <dCodInt>100A57</dCodInt>
                <dDesProSer>TESTING ITEM</dDesProSer>
                <cUniMed>77</cUniMed>
                <dDesUniMed>UNI</dDesUniMed>
                <dCantProSer>1</dCantProSer>
                <gValorItem>
                    <dPUniProSer>5000</dPUniProSer>
                    <dTotBruOpeItem>5000</dTotBruOpeItem>
                    <gValorRestaItem>
                        <dDescItem>0</dDescItem>
                        <dDescGloItem>0</dDescGloItem>
                        <dAntPreUniIt>0</dAntPreUniIt>
                        <dAntGloPreUniIt>0</dAntGloPreUniIt>
                        <dTotOpeItem>5000</dTotOpeItem>
                    </gValorRestaItem>
                </gValorItem>
                <gCamIVA>
                    <iAfecIVA>1</iAfecIVA>
                    <dDesAfecIVA>Gravado IVA</dDesAfecIVA>
                    <dPropIVA>100</dPropIVA>
                    <dTasaIVA>10</dTasaIVA>
                    <dBasGravIVA>4545.45454545</dBasGravIVA>
                    <dLiqIVAItem>454.54545455</dLiqIVAItem>
                    <dBasExe>0</dBasExe>
                </gCamIVA>
            </gCamItem>
        </gDtipDE>
        <gTotSub>
            <dSubExe>0</dSubExe>
            <dSubExo>0</dSubExo>
            <dSub5>0</dSub5>
            <dSub10>5000</dSub10>
            <dTotOpe>5000</dTotOpe>
            <dTotDesc>0</dTotDesc>
            <dTotDescGlotem>0</dTotDescGlotem>
            <dTotAntItem>0</dTotAntItem>
            <dTotAnt>0</dTotAnt>
            <dPorcDescTotal>0</dPorcDescTotal>
            <dDescTotal>0</dDescTotal>
            <dAnticipo>0</dAnticipo>
            <dRedon>0</dRedon>
            <dTotGralOpe>5000</dTotGralOpe>
            <dIVA5>0</dIVA5>
            <dIVA10>455</dIVA10>
            <dLiqTotIVA5>0</dLiqTotIVA5>
            <dLiqTotIVA10>0</dLiqTotIVA10>
            <dTotIVA>455</dTotIVA>
            <dBaseGrav5>0</dBaseGrav5>
            <dBaseGrav10>4545</dBaseGrav10>
            <dTBasGraIVA>4545</dTBasGraIVA>
        </gTotSub>
    </DE>
    <Signature xmlns="http://www.w3.org/2000/09/xmldsig#">
        <SignedInfo>
            <CanonicalizationMethod Algorithm="http://www.w3.org/2001/10/xml-exc-c14n#WithComments"/>
            <SignatureMethod Algorithm="http://www.w3.org/2001/04/xmldsig-more#rsa-sha256"/>
            <Reference URI="#12341234123412341234123412341234123412341234">
                <Transforms>
                    <Transform Algorithm="http://www.w3.org/2000/09/xmldsig#enveloped-signature"/>
                    <Transform Algorithm="http://www.w3.org/2001/10/xml-exc-c14n#"/>
                </Transforms>
                <DigestMethod Algorithm="http://www.w3.org/2001/04/xmlenc#sha256"/>
                <DigestValue>digestValueData</DigestValue>
            </Reference>
        </SignedInfo>
        <SignatureValue>signatureValueData</SignatureValue>
        <KeyInfo>
            <X509Data>
                <X509Certificate>x509CertificateData</X509Certificate>
            </X509Data>
        </KeyInfo>
    </Signature>
    <gCamFuFD>
        <dCarQR>urlSifen</dCarQR>
    </gCamFuFD>
</rDE>
```
