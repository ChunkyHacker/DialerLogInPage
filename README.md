<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agent web client: Phone Log In</title>
</head>
<header>
</header>
    <body onresize="browser_dimension();" onload="browser_dimension">
        <a href="">
            <font class="sb_text">Timeclock</font>
        </a>
        <font class="sb_text"> | </font>
        <a href="">
            <font class="sb_text">Old Agent Screen</font>
        </a>
        <br>
        <!--TABLE-->
            <table width="'100%">
                <tbody>
                    <tr>
                        <td></td>
                        <!-- INTERNATIONALIZATION-LINKS-PLACEHOLDER-VICIDIAL -->
                    </tr>
                </tbody>
            </table>
        <form action="" name="vicidial_form" method="post">
            <input type="hidden" name="DB" id="" value="0">
            <input type="hidden" name="JS_Browser_Height" id="JS_Browser_Height" value="1115">
            <br>
            <br>
            <br>
            <center>
                <table width="460" cellpadding="3" cellspacing="0" bgcolor="#D6E3B2">
                    <tbody>
                        <tr bgcolor="white">
                            <td align="left" valign="bottom" bgcolor="#284F01" width="170">
                                <img src="https://hosted101.apntelecom.com/agent/images/vicidial_admin_web_logo.png" alt="Agent Screen" border="0" height="45" width="170">
                            </td>
                            <td align="center" valign="middle" bgcolor="#284F01">
                                <font class="sh_text_white" color="white">Phone Log In</font>
                            </td>
                        </tr>
                        <tr>
                            <td align="left" colspan="2">
                                <font size="1">&nbsp;</font>
                            </td>
                        </tr>
                        <tr>
                            <td align="right">
                                <font class="skb_text">Phone Log in:</font>
                            </td>
                            <td align="left">
                                <input type="text" name="phone_login" id="" size="10" maxlength="20" value="">
                            </td>
                        </tr>
                        <tr>
                            <td align="right">
                                <font class="skb_text">Phone Password:</font>
                            </td>
                            <td align="left">
                                <input type="password" name="phone_pass" id="" size="10" maxlength="20" value>
                            </td>
                        </tr>
                        <tr>
                            <td align="center" colspan="2">
                                <input type="submit" name="SUBMIT" id="" value="SUBMIT">
                                 &nbsp; 
                                <span id="LogInReset"></span>
                            </td>
                        </tr>
                        <tr>
                            <td align="left" colspan="2">
                                <font class="body_Tiny">
                                    <br>
                                    Version: 2.14-531c &nbsp; &nbsp; &nbsp; BUILD:170808-1014
                                </font>
                            </td>
                        </tr>
                    </tbody>

                </table>
            </center>
        </form>
        
    </body>
</html>
