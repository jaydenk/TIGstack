
-------------------------------------------------------------------
This file outlines changes since the last release of MIBs.

It is very strongly recommended that you load and compile ALL of
the MIBs provided.

Please load the 'hpicfOid.mib' before loading the other specific
MIBs.  This is due to the fact that the 'hpicfOid.mib' is the
parent MIB to most of the HP device specific MIBs.
-------------------------------------------------------------------

hpicfAuth.mib


       - Added ' hpSwitchRadiusFqdnRetry' MIB object 
                      in 'hpSwitchRadiusConfig' table."

       - Added new MIB objects for NAS-ID for RADIUS group
                      hpSwitchAAAServerGroupNasId."

       - Added new MIB objects -
                      hpSwitchTacacsServerAddressType,
                      hpSwitchTacacsServerAddress,
                      hpTacacsStatsTacacsServerAdrType,
                      hpTacacsStatsTacacsServerAddr."

       - Added new MIB objects,

                      hpSwitchAAAServerGroupNasTable 
                      HpSwitchAAAServerGroupNasEntry 
       
                      hpSwitchAAAServerGroupNasProtocolType    
                      hpSwitchAAAServerGroupNasIndex           
                      hpSwitchAAAServerGroupNasName            
                      hpSwitchAAAServerGroupNasId              
                      hpSwitchAAAServerGroupNasStatus          
  


hpicfAutz.mib

      -  Added hpSwitchAutzUserRoleTaggedVlanList,
         hpSwitchAutzUserRoleCachedReauthPeriod  to  HpSwitchAutzUserRoleEntry

      -  Added hpSwitchAutzUserRolePortMode to  HpSwitchAutzUserRoleSubEntry 

      -  Added   hpSwitchAutzUserRoleTunneledNodeServerDownloadableRole,
         to HpSwitchAutzUserRoleEntry

      -  Added new table hpSwitchAutzUserRoleSubTable, 
                                -hpSwitchAutzUserRoleSubType,hpSwitchAutzUserRoleAdminEdgePort
                 hpSwitchAutzUserRolePoePriority,hpSwitchAutzUserRolePoeAllocBy,
                 hpSwitchAutzUserRoleSubTypeRowStatus,hpSwitchAutzUserRolePortMode


hpicfDevConf.mib


       - "Added new object hpSwitchProfMode in table hpSwitchDevProfTable."

       - New MIB object,
                   hpSwitchProfMode 




hpicfDeviceIdentity.mib


       - Added new objects,
            hpicfCdpBypassTable,HpicfCdpBypassEntry 
             hpicfDevIdentityCdpType         
             hpicfDevIdentityCdpValue       
             hpicfDevIdentityCdpRowStatus   
  

hpicfDot1x.mib

        - Added new objects,

           hpicfAuthMaxEapReq,
           hpicfDot1xPaePortEapRetriesGroup



hpicfSyslog.mib

          - Added 'authOrder' entry in HpicfSyslogSystemModule"



hpicfTunneledNode.mib


          - Added hpicfTunneledNodeReservedVlanId object to the  hpicfTunneledNodeTable."
          - Added hpicfTunneledNodeVlanMode object to the  hpicfTunneledNodeTable."
  


hpicfUfd.mib

          - Added new MIB object hpicfUfdLinksTransitionDelay    
      

hpicfUsrAuth.mib

         - Added in HpicfUsrAuthOrderPortEntry new entry,
                  hpicfUsrAuthOrderFirst,
                  hpicfUsrAuthOrderSecond,
                  hpicfUsrAuthOrderLmaFallback,
                  hpicfUsrAuthPriorityFirst,
                  hpicfUsrAuthPrioritySecond
                  Added hpicfUsrAuthOrderPortsGroup.

         - Added in HpicfUsrAuthBypassPortEntry new objects,
                  hpicfUsrAuthBypassAdminStatus,
                  hpicfUsrAuthDeviceIdentityName 

         - Added new MIB object hpicfMacAuthRadiusServer in 
                  hpicfUsrAuthMacAuthConfigEntry.


hpSwitchConfig.mib


          - Added new MIB hpSwitchTrunkTable
          - Added new MIB objects, HpSwitchTrunkEntry
                                     hpSwitchTrunkIndex,              
                                    hpSwitchTrunkMinActiveLinks,     
                                    hpSwitchTrunkLacpEnableTimer,    

