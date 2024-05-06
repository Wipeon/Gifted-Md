#============================================================================================#   
#                                      GIFTED－MD                                             # 
#                                                                                             # 
#                                   VERSION ：2．5．0                                          # 
#                                                                                             # 
#                                                                                             # 
#           ██████╗ ██╗███████╗████████╗███████╗██████╗     ███╗   ███╗██████╗                # 
#          ██╔════╝ ██║██╔════╝╚══██╔══╝██╔════╝██╔══██╗    ████╗ ████║██╔══██╗               # 
#          ██║  ███╗██║█████╗     ██║   █████╗  ██║  ██║    ██╔████╔██║██║  ██║               # 
#          ██║   ██║██║██╔══╝     ██║   ██╔══╝  ██║  ██║    ██║╚██╔╝██║██║  ██║               # 
#          ╚██████╔╝██║██║        ██║   ███████╗██████╔╝    ██║ ╚═╝ ██║██████╔╝               # 
#           ╚═════╝ ╚═╝╚═╝        ╚═╝   ╚══════╝╚═════╝     ╚═╝     ╚═╝╚═════╝                # 
#                                                                                             # 
#                                                                                             # 
#                                                                                             # 
#                                                                                             # 
#=============================================================================================# 
#                                                                 
#    * @project_name : Gifted-Md
#    * @author : @GiftedTech
#    * @youtube : https://www.youtube.com/@giftedtechnexus
#    * @description : Gifted-Md ,A Multi-functional whatsapp bot md.
#    * @version 2.5.0
# 
# Don't change this [ /GiftedTech/ ] name!
# Change from below link, else bot not works!

 

FROM quay.io/sampandey001/secktor

RUN git clone https://github.com/mouricedevs/Gifted-Md.git /root/Itxxwasi

# Clear npm cache and remove node_modules directories
RUN npm cache clean --force
RUN rm -rf /root/Gifted/node_modules

# Install dependencies
WORKDIR /root/Gifted
RUN npm install

# Add additional Steps To Run...
EXPOSE 3000
CMD ["npm","start" ]
# IF YOU ARE MODIFYING THIS BOT DONT CHANGE THIS  RUN rm -rf /root/Gifted/node_modules
