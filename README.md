# Network-Simulation
Computer network simulation using C++ and NS-3

## Protocols (Ongoing)

* TCP/IP
* UDP/IP
* CSMA/CD (LAN)
* CSMA/CA (WiFi)


## Topologies (Ongoing)


Point-to-Point:  
```
//
//       10.1.1.0
// n0 -------------- n1
//    point-to-point
//
```

LAN:  
```
//       10.1.1.0
// n0 -------------- n1   n2   n3   n4
//    point-to-point  |    |    |    |
//                    ================
//                      LAN 10.1.2.0
```

Wireless/Wifi:  
```
//   Wifi 10.1.3.0
//                 AP
//  *    *    *    *
//  |    |    |    |    10.1.1.0
// n5   n6   n7   n0 -------------- n1   n2   n3   n4
//                   point-to-point  |    |    |    |
//                                   ================
//                                     LAN 10.1.2.0
```