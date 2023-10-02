owasys4x_base
=============

Uso de los perifericos del owasys con los programas en C y su propia base de datos en REDIS

### About

This is your project's README.md file. It helps users understand what your
project does, how to use it and anything else they may need to know.


### Encryption key
```
$ACME_INTERNAL_PASS
```

### Data structure

{
    "gateway_key": "",
    "timestamp": 0,
    "data": {
        "gateway_info": {
            "eth_ip": "-",
            "vpn_ip": "-",
            "ping_acme": "-",
            "total_space": 0,
            "used_space": 0,
            "used_space_percent": 0,
            "free_space": 0,
            "num_gps_sat": 0,
            "memory_usage_percent": 0,
            "temperature": 0,
            "vbat": 0
        },
        "gps": {
            "pos_valid": 0,
            "old_pos": 1,
            "total": 0,
            "nav_status": 0,
            "latitude": 0,
            "longitude": 0,
            "altitude": 0,
            "haccuracy": 0,
            "vaccuracy": 0,
            "speed": 0,
            "course": 0,
            "hdop": 0,
            "vdop": 0,
            "tdop": 0,
            "num_sat": 0
        },
        "imu": {
            "accel_x": 0,
            "accel_y": 0,
            "accel_z": 0
        },
        "sensor_estado": {
            "state": "init"
        }
    }
}
