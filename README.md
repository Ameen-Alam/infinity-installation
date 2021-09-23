# Infinity-installation


timedatectl

NTP syncrinized should be yes


ulimit -a

open files (-n) 10240

vi /etc/security/limits.conf

root    hard    nofile  102400

root    soft    nofile  10240


need to whitelist 3rd part

https://docs.avoka.com/Insights/SetUpInsights.htm


page 19 google 443 / apple 2196 2195

https://docs.kony.com/8_x_PDFs/konyfabric/konyfabric_installation-guide-windows.pdf


PAM 7.10

keycloak 10.0

https://docs.temenos.com/docs/Solutions/Infinity/Installation/Infinity_Installation/Infinity_Installation/Manual%20Installation/Onboarding%20Setup.html

JBoss 7.3.4
