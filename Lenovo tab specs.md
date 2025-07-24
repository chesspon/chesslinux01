モデル: Miix 300-10IBY
CPU: Atom Z3735F
RAM: 2GB
Display: 1280x800

ついでにAmazon Fireと

RAZR 40 Ultraも

chess@chesspro4:~/Documents/Docs$ sudo systemctl restart NetworkManager
Job for NetworkManager.service failed because the control process exited with error code.
See "systemctl status NetworkManager.service" and "journalctl -xeu NetworkManager.service" for details.
chess@chesspro4:~/Documents/Docs$ systemctl status NetworkManager.service
× NetworkManager.service - Network Manager
     Loaded: loaded (/lib/systemd/system/NetworkManager.service; enabled; preset: enabled)
     Active: failed (Result: exit-code) since Wed 2025-07-23 18:08:03 CEST; 49s ago
   Duration: 19min 34.713s
       Docs: man:NetworkManager(8)
    Process: 6275 ExecStart=/usr/sbin/NetworkManager --no-daemon (code=exited, status=1/FAILURE)
   Main PID: 6275 (code=exited, status=1/FAILURE)
        CPU: 64ms

Jul 23 18:08:03 chesspro4 systemd[1]: NetworkManager.service: Scheduled restart job, restart counter is at 5.
Jul 23 18:08:03 chesspro4 systemd[1]: Stopped NetworkManager.service - Network Manager.
Jul 23 18:08:03 chesspro4 systemd[1]: NetworkManager.service: Start request repeated too quickly.
Jul 23 18:08:03 chesspro4 systemd[1]: NetworkManager.service: Failed with result 'exit-code'.
Jul 23 18:08:03 chesspro4 systemd[1]: Failed to start NetworkManager.service - Network Manager.
chess@chesspro4:~/Documents/Docs$ 