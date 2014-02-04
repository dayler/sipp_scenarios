http://wiki.sipfoundry.org/display/sipXecs/Using+SIPp+to+run+performance+tests

UAS
===

sipp -sf descriptor/uas.xml -p 5066 -i 127.0.0.1 -rsa 127.0.0.1:5060 127.0.0.1:5088  -trace_err -trace_msg -m 200

UAC
===

sipp -sf descriptor/uac.xml -p 5088 -i 127.0.0.1 -rsa 127.0.0.1:5060 127.0.0.1:5066 -trace_err -trace_msg -l 1 -m 200