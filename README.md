<div align="center">

## Change Image Format \(jpg, bmp, png\)


</div>

### Description

I always wanted that the functionality to convert an image from one format to another should be available in the programming language itself. This dream has come true with .NET. There are many applications (dealing with images) in which we might want to save an image of any format in some other format (example: bmp to jpg is very common as it decreases the file size considerably without significant loss of quality). This can be done very easily in .NET.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Rahul Vyas \(coder000\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/rahul-vyas-coder000.md)
**Level**          |Beginner
**User Rating**    |4.5 (18 globes from 4 users)
**Compatibility**  |VB\.NET
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__10-15.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/rahul-vyas-coder000-change-image-format-jpg-bmp-png__10-3429/archive/master.zip)





### Source Code

		<strong><font face="verdana" size="4">Image Format </font></strong>
		<font face="verdana" size="4"><STRONG>(Graphics; VB.NET)</STRONG></font>
		<font face="verdana" size="2">
			<p>I always wanted that the functionality to convert an image from
  one format to another should be available in the programming
  language itself. This dream has come true with .NET. There are many
  applications (dealing with images) in which we might want to save an
  image of any format in some other format (example: bmp to jpg
  is very common as it decreases the file size considerably without
  significant loss of quality). This can be done very easily in .NET.</p>
			<p>We can accomplish this using the
		</FONT>
		<font face="Courier New" size="2">
			Save</FONT><font face="verdana" size="2">
			method of
		</FONT>
		<font face="Courier New" size="2">
			Bitmap</FONT><font face="verdana" size="2">
			object.</p>
 <p>The following code reads a <b>bmp</b> image file into a bitmap object
 and then saves it back in <b>jpg</b> format. </p>
		</FONT>
		<font face="Courier New" size="2">
			<p><font color="#0000FF">Dim</font> btmp <font color="#0000FF">As
  New</font> Bitmap("C:\myimage.bmp")</p>
 <p>btmp.Save("C:\myimage.jpg",System.Drawing.Imaging.ImageFormat.Jpeg)</p>
		</FONT>
		<font face="verdana" size="2">
			<p>The first line loads the bitmap from the file myimage.bmp located
  in C:\ into a bitmap object - btmp.</p>
 <p>The second line saves the loaded bitmap in Jpeg
 format with myimage.jpg as filename.</p>
 <p>Other formats specified in ImageFormat class include bmp, gif, jpeg, tiff, png, etc.</p>
			<FONT face="Courier New">
			<P><FONT face="Verdana">Feedback and comments are most welcome</FONT>

