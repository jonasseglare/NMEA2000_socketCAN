add_library(NMEA2000_SocketCan
  NMEA2000_SocketCan.h
  NMEA2000_SocketCan.cpp
  )

target_link_libraries(NMEA2000_SocketCan
  nmea2000
  )
