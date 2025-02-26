---
title: KSPROPERTY\_DVDCOPY\_REGION
description: The KSPROPERTY\_DVDCOPY\_REGION property specifies the DVD copy-protection region according to language restrictions.
keywords: ["KSPROPERTY_DVDCOPY_REGION Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_DVDCOPY_REGION
api_location:
- ksmedia.h
api_type:
- HeaderDef
ms.date: 11/28/2017
ms.localizationpriority: medium
---

# KSPROPERTY\_DVDCOPY\_REGION


The KSPROPERTY\_DVDCOPY\_REGION property specifies the DVD copy-protection region according to language restrictions.

## <span id="ddk_ksproperty_dvdcopy_region_ks"></span><span id="DDK_KSPROPERTY_DVDCOPY_REGION_KS"></span>


### Usage Summary Table

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Get</th>
<th>Set</th>
<th>Target</th>
<th>Property descriptor type</th>
<th>Property value type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Pin</p></td>
<td><p><a href="/windows-hardware/drivers/stream/ksproperty-structure" data-raw-source="[&lt;strong&gt;KSPROPERTY&lt;/strong&gt;](./ksproperty-structure.md)"><strong>KSPROPERTY</strong></a></p></td>
<td><p><a href="/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-_ks_dvdcopy_region" data-raw-source="[&lt;strong&gt;KS_DVDCOPY_REGION&lt;/strong&gt;](/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-_ks_dvdcopy_region)"><strong>KS_DVDCOPY_REGION</strong></a></p></td>
</tr>
</tbody>
</table>

 

The property value (operation data) is a KS\_DVDCOPY\_REGION structure that describes the region code for the nationality or language.

## Remarks

For more information about language restrictions, see [DVD Regionalization](./dvd-regionalization.md) and [DVD Copyright Protection](./dvd-copyright-protection.md).

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ksmedia.h (include Ksmedia.h)</td>
</tr>
</tbody>
</table>

## See also


[**KS\_DVDCOPY\_REGION**](/windows-hardware/drivers/ddi/ksmedia/ns-ksmedia-_ks_dvdcopy_region)