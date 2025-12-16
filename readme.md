## Hosts File ที่รวบรวม Domain ของเว็บที่ให้บริการสมัครบริการเสริม (โดยที่ไม่แจ้งผู้ใช้ให้ทราบ)
> หรือที่เรียกว่า **SMS กินเงิน / Content เสียเงิน / บริการอีแอบ**

### สามารถประยุกต์ใช้ได้กับ
**Windows Hosts File**: แนะนำให้ใช้กับ [HOSTS Manager (Windows)](https://github.com/henrypp/hostsmgr)
> *ไม่แนะนำ [HostsMan](http://www.abelhadigital.com/hostsman) เนื่องจากยังไม่รองรับการ Hotlink Hosts File จาก GitHub Raw*

**ระบบปฏิบัติการอื่นๆ ในคอมพิวเตอร์**: แนะนำให้ใช้กับ [personalDNSfilter](https://zenz-solutions.de/personaldnsfilter)

**มือถือ Android ที่ Root แล้ว**: ใช้กับแอพฯ [AdAway](https://github.com/AdAway/AdAway)

**มือถือ Android ที่ไม่ได้ Root**: สามารถใช้ได้กับแอพฯ
- [AdAway](https://github.com/AdAway/AdAway)
- [DNS66](https://github.com/julian-klode/dns66)
- [DNSNet](https://github.com/t895/DNSNet)
- [Nebulo](https://github.com/Ch4t4r/Nebulo)
- [personalDNSfilter](https://zenz-solutions.de/personaldnsfilter)
> **ไม่แนะนำ**
> - Blokada
> - [NetGuard](https://github.com/M66B/NetGuard) *เนื่องจากสามารถโหลด Hosts File ได้เพียงแหล่งเดียว*

**โปรแกรม Web Browser**: สามารถใช้ได้กับ [uBlock Origin](https://github.com/gorhill/uBlock)

**สำหรับผู้ที่ต้องการควบคุมภายในวง Lan**: แนะนำให้ใช้กับ
- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)
- [Pi-Hole](https://github.com/pi-hole/pi-hole)

### แนะนำเพิ่มเติมสำหรับผู้ใช้ Android
ผู้ใช้สามารถติดตั้งส่วนเสริม uBlock Origin ได้ ภายในแอพฯ [Firefox for Android](https://play.google.com/store/apps/details?id=org.mozilla.firefox) หรือ Browser ที่คล้ายกัน เช่น
- [Fennec F-Droid](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid)
- [IronFox](https://github.com/ironfox-oss/IronFox)
- [WebLibre](https://github.com/FaFre/WebLibre)

### หมายเหตุ
Hosts File นี้ไม่สามารถแก้ปัญหาหรือป้องกันการสมัครโดยวิธีอื่น นอกเหนือจากการถูกโฆษณาประเภท Popunder และการถูก Redirect ไปยังเว็บไซท์เหล่านั้นโดยอัตโนมัติ เช่น
- การถูกสมัครโดยช่องทางการส่ง SMS โดยอัตโนมัติของแอพพลิเคชั่นที่ไม่พึงประสงค์ (ซึ่งส่วนมากมักมีโฆษณา และ/หรือ ขอสิทธิ์ในการเข้าถึงและส่งข้อความ SMS รวมถึงการโทรออก)
- การสุ่มเบอร์โทรศัพท์ของเจ้าของบริการเสียเงิน โดยมีการใช้ระบบตอบรับอัตโนมัติ หรือมีพนักงานพูดสาย ซึ่งหากเผลอตอบ "ตกลง" "ใช่" "ครับ" หรือ "ค่ะ" จะถือว่าเป็นคำยืนยันการสมัครใช้บริการนั้นๆ เป็นต้น

ทั้งนี้ทั้งนั้น บางเว็บไซท์อาจไม่ได้อัพเดทเพิ่มเข้ามาได้ทัน แต่จะพยายามรวบรวมให้มากที่สุดเท่าที่จะทำได้



