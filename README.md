-=(Exidy2_Senhor notes)=-

Tested: Working Video 720p, 1080p & Sound.

___
# [Exidy Universal Game Board II](https://www.system16.com/hardware.php?id=991)
<p>Thank you to the following members of the MiSTer community: DarFPGA, Boogermann, misterretrowolf, Sorgelig, & Jotego.</p>
<p>Thank you to the following for moral support and testing: Chris Vasquez, Guru Guy & 240p.</p>

<p>The first iteration of the Exidy Universal Game Board 2 was found in Side Trak which was a black and white game released in 1980.  The same hardware was expanded on several times to include color graphics and dedicated audio hardware.</p>

<strong>Main CPU :</strong> MOS 6502 - T65  
<strong>Audio CPU:</strong> MOS 6502 - T65

<strong>Sound Effects:</strong> Motorola MC6840 Programmable Timer Module (PTM) - Modfied version of DarFPGA's Bezerk sound effects implementation.

<strong>Music/Tone Generator:</strong> Intel 8053 - Sorgelig

<strong>PIA:</strong> Motorola MC6821 X 2 - John E. Kent - www.OpenCores.Org

<strong>RIOT:</strong> MOS 6532 RAM I/O Timer - Thierry DAVROUX

<strong>Video resolution:</strong> 256x256 @ 60Hz  

<h2>Compatible Platforms</h2>
<li>MiSTer FPGA</li>

<h2>Compatible Games</h2>
<blockquote>
<p dir="auto"><strong>ROMs NOT INCLUDED:</strong> By using this core you agree to provide your own roms.</p>
</blockquote>

<li>TARG (1980)</li>
<li>Spectar (1980)</li>
<li>Venture (1981)</li>
<li>Mouse Trap (1981)</li>
<li>Pepper II (1982)</li>

<h2>Not Working</h2>
<li>Teeter Torture</li>
<li>Side Trak</li>
<li>Fax</li>
<li>Fax II</li>

<h2>Issues</h2>
Not all analog sound effects are implemented, this affects TARG & Spectar (crash/noise sounds).

<h2>Coming Soon</h2>
High Score Saves
