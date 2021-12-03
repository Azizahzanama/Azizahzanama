<!DOCTYPE html>
<html lang="en">
    <head>
        <title>FORM HTML</title>
    </head>
    <body> 
    <fieldset style="width:40%">
        <h2>Mendaftar</h2>
        <p>Gratis (sampai kapan pun)</p>
        
        
        <form name="input" action="input.php" method="get">
        <table>
            <tr>
                <td>Nama Depan :</td>
                <td><input type="text" name="firstname" style="width:250px" /></td>
            </tr>
            <tr>
                <td>Nama Belakang :</td>
                <td><input type="text" name="lastname" style="width:250px" /></td>
            </tr>
            <tr>
                <td>Email Anda :</td> 
                <td><input type="email" id="email" name="email" style="width:250px" /></td>
            </tr>
            <tr>
                <td>Masukkan Ulang Email :</td> 
                <td><input type="email" id="email" name="email" style="width:250px" /></td>
            </tr>
            <tr>
                <td>Kata Sandi Baru :</td> 
                <td><input type="password" id="pwd" name="pwd" style="width:250px" /></td>
            </tr>
            <tr>
                <td>Saya seorang :</td>
                <td>
                    <select><option> Pilih Jenis Kelamin 
                        <option> Wanita
                        <option> Pria
                    </select> 
                </td>
            </tr>
            <tr>
                <td rowspan="2">Tanggal lahir :</td>
                <td>
                    <select name="date"><option> Tanggal
                        <option> 01</option>
                        <option> 02</option>
                        <option> 03</option>
                        <option> 04</option>
                        <option> 05</option>
                        <option> 06</option>
                        <option> 07</option>
                        <option> 08</option>
                        <option> 09</option>
                        <option> 10</option>
                        <option> 11</option>
                        <option> 12</option>
                        <option> 13</option>
                        <option> 14</option>
                        <option> 15</option>
                        <option> 16</option>
                        <option> 17</option>
                        <option> 18</option>
                        <option> 19</option>
                        <option> 20</option>
                        <option> 21</option>
                        <option> 22</option>
                        <option> 23</option>
                        <option> 24</option>
                        <option> 25</option>
                        <option> 26</option>
                        <option> 27</option>
                        <option> 28</option>
                        <option> 29</option>
                        <option> 30</option>
                        <option> 31</option>
                    </select>
                
                    <select name="month"><option> Bulan
                        <option>Januari</option>
                        <option>Februari</option>
                        <option>Maret</option>
                        <option>April</option>
                        <option>Mei</option>
                        <option>Juni</option>
                        <option>Juli</option>
                        <option>Agustus</option>
                        <option>September</option>
                        <option>Oktober</option>
                        <option>November</option>
                        <option>Desember</option>
                    </select>
                </td>
            </tr>

            <tr>
                <td colspan="1">
                   <select name="year"><option> Tahun
                        <option >2000</option>
                        <option >2001</option>
                        <option >2002</option>
                        <option>2003</option>
                        <option >2004</option>
                        <option>2005</option>
                        <option>2006</option>
                        <option>2007</option>
                        <option>2008</option>
                        <option>2009</option>
                        <option>2010</option>
                        <option>2011</option>
                        <option>2012</option>
                        <option>2013</option>
                        <option>2014</option>
                        <option>2015</option>
                    </select>
                </td>
            </tr>
            <td></td>
            <td colspan="2" align="left"> Mengapa saya perlu mengisinya ?</td>
            <tr>
            <td></td>
            <td colspan="2"><input type="submit" value="Mendaftar"></td>
            </tr>
            
        </table>
        </form>
    </fieldset>
    </body>
</html>
