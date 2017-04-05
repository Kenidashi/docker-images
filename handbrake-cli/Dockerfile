FROM dbarton/jdownloader
LABEL org.freenas.interactive="false"				\
      org.freenas.version="2"					\
      org.freenas.upgradeable="true"				\
      org.freenas.expose-ports-at-host="true"			\
      org.freenas.autostart="true"				\
      org.freenas.volumes="[					\
          {							\
              \"name\": \"/input\",			\
              \"descr\": \"Configuration files directory\"	\
          },							\
          {							\
              \"name\": \"/output\",		\
              \"descr\": \"downloads Folder\"			\
          }							\	
       ]"							\
       org.freenas.settings="[					\
          {							\
              \"env\": \"HANDBRAKE_GID\",			\
              \"descr\": \"PGID assigned upon creation\",	\
              \"optional\": true				\
          },							\
          {							\
              \"env\": \"HANDBRAKE_UID\",			\
              \"descr\": \"PUID assigned upon creation\",	\
              \"optional\": true				\
          }							\
      ]"        
