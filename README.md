# qb-oxyrun
Oxy run for QB


add this to your qb-target config. under peds option

 ["oxy"] = {
        model = 'g_m_m_armgoon_01',
    coords = vector4(168.5052, -1505.21, 29.272, 139.6),
    minusOne = true, 
    freeze = true,
    invincible = true,
    blockevents = true,
    animDict = 'abigail_mcs_1_concat-0',
    anim = 'csb_abigail_dual-0',
    flag = 1,
    scenario = 'PROP_HUMAN_STAND_IMPATIENT',
    target = {
      options = {
        {
          type = "client", 
          event = 'nh-context:testMenu',
          icon = "fas fa-capsules",  
          label = 'Speak to the gang member',
          targeticon = 'fas fa-eye', 
        }
      },
      distance = 2.5,
    },
    currentpednumber = 0,
    },
    
    
    ensure you have oxy as a item in your qb-core/shared.lua
    
    ['oxy'] 				 		 = {['name'] = 'oxy',				    		['label'] = 'Prescription Oxy',			['weight'] = 0,			['type'] = 'item',		['image'] = 'oxy.png',					['unique'] = false,		['useable'] = true,		['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'The Label Has Been Ripped Off'},


