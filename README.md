# jquery-inline-message-box
<b>Inline Message Box plugin</b> is a light weight <b>(4.26 KB)</b> jQuery plugin. Features include 6 types of message box, no additional css required, closable, auto closable, option parameters for full control of message box functionality etc.. You can use it very easily.
## How to use it
<pre>&lt;script src=&quot;http://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js&quot;&gt;&lt;/script&gt;
&lt;script src=&quot;inline-message-box.min.js&quot;&gt;&lt;/script&gt;</pre>
## Configuration
<div class="table-responsive">
<table class="table table-striped">
<th>Option</th>
<th>Default Value</th>
<th>Description</th>
<tr>
<td>messageBoxType</td>
<td>null</td>
<td>Define the message box type here. 6 types of message box type is available. if this option is null, then it is the <b>default</b> message box. Other types are <b>success</b>, <b>error</b>, <b>fatalerror</b>, <b>warning</b> & <b>info</b>.</td>
</tr>
<tr>
<td>message</td>
<td>null</td>
<td>Set your message here.</td>
</tr>
<tr>
<td>closeButton</td>
<td>true</td>
<td>If you don't need 'close' button, set to <b>false</b>.</td>
</tr>
<tr>
<td>enabled</td>
<td>false</td>
<td>If you want to close message box automatically, then it set to <b>true</b>.</td>
</tr>
<tr>
<td>milliseconds</td>
<td>30000</td>
<td>This value is used for automatically close this message within '30' sec.</td>
</tr>
</table>
</div>
<pre>
<div class="success-demo"></div>
<script>
    $(document).ready(function() {
        $(".success-demo").BitCompiler().showInlineMessageBox({
            messageBoxType: "success",
            message: "This is the auto close <b>success</b> message",
            autoClose: {
                enabled: true,
                milliseconds: 30000
            }
        });
    });
</script>
</pre>
<a href='https://www.bitcompiler.com/jquery-inline-message-box' class="btn btn-lg btn-primary">Demo</a>
