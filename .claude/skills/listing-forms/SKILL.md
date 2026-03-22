---
name: listing-forms
description: |
  **Listing Appointment Forms Filler**: Automatically fill out the 4 standard NJ listing appointment forms (Residential Listing Agreement, Lead Paint Disclosure, Consumer Information Statement, and Seller Property Condition Disclosure) with property address, seller info, and Jenise's agent details.
    - MANDATORY TRIGGERS: listing forms, fill forms, listing appointment, listing paperwork, fill out listing agreement, lead paint form, property disclosure form, consumer information statement, listing packet, prepare forms, new listing, fill the forms, complete the forms, listing docs
      - Also trigger when Jenise mentions going on a listing appointment, preparing paperwork for a listing, or needing forms filled for a new property/seller
        - This skill requires the 4 blank template PDFs to be uploaded or available in the uploads folder
        ---

        # Listing Appointment Forms Filler

        This skill fills out the 4 standard NJ listing appointment forms for Jenise Buckalew at Green Light Realty LLC.

        ## Required Information

        At minimum: Property address and Seller name(s)

        Optional (defaults): Commission rate (5%), MLS fee ($200), Cooperating broker commission (2%), County (auto from city), Seller phone/email, Listing price, Block/Lot numbers

        ## Agent Info (Pre-filled)
        - Agent: Jenise Buckalew, REALTOR
        - Brokerage: Green Light Realty LLC
        - Office: 1109 Englishtown Rd, Old Bridge, NJ 08857
        - Phone: (347) 393-5993
        - Email: jenisesellsnj@gmail.com

        ## The 4 Forms

        ### 1. Residential Listing Agreement (Form 150)
        Fill: Seller names, Primary Address, County, exclusive broker checkbox, all 3 agency checkboxes, MLS fee (Section 4), Commission % in Section 5(a)(i/ii/iii), Commission split on page 4, authorize splits checkbox Section 7(a), Section 7(b) table Yes/offer for Subagents/Buyers Brokers/Transaction Brokers under Sale, authorize disclosure Section 7(c)

        ### 2. Lead Paint Disclosure (8/16)
        Check: Seller has no knowledge, Seller has no reports. Listing Agent = Jenise Buckalew. Leave purchaser sections blank.

        ### 3. Consumer Information Statement (CIS)
        Page 2 For Sellers: Licensee name = Jenise Buckalew. Leave signature/date blank.

        ### 4. Seller Property Condition Disclosure (Form 140)
        Page 2: Seller names only. Leave ALL questions blank for seller to complete.

        ## Key Coordinates (PDF coords, y=0 at top, pdf_width: 612, pdf_height: 792)

        Listing Page 1: Seller names [131,224,430,236], Address [183,246,565,258], County [478,378,565,390], Exclusive broker [215,411,226,422], Seller Agent [47,510,56,521], Dual Agent [47,532,56,543], Designated [47,554,56,565]

        Listing Page 2: MLS [420,127,565,139], Commission exclusive [409,622,530,634], non-exclusive [82,678,200,690]

        Listing Page 3: Commission regardless [202,92,330,104]

        Listing Page 4: Split amount [429,236,535,248], Auth splits [83,358,94,369], Sub Yes [274,468,285,479], Sub offer [340,468,385,480], Buyers Yes [274,485,285,496], Buyers offer [340,485,385,497], Trans Yes [274,502,285,513], Trans offer [340,502,385,514], Auth disclose [83,535,94,546]

        Lead Paint Page 1: No knowledge [68,393,95,405], No reports [68,432,95,444], Agent name [107,667,460,679]

        CIS Page 2: Licensee name [73,555,210,567]

        Disclosure Page 2: Seller names [80,143,565,155]

        ## NJ County Loo-k-u-p

        nMaimded:l elsiesxt:i nSga-yfroervmisl
        ldee,s cOrlidp tBiroind:g e|,
          E a*s*tL iBsrtuinnsgw iAcpkp,o iEndtimseonnt,  FWooromdsb rFiidlglee,r *P*e:r tAhu tAommbaotyi,c aNlelwy  Bfriulnls woiuctk ,t hPei s4c asttaawnadya,r dM oNnJr olei sTtoiwnngs haippp
          oMionntmmoeuntth :f oEramtso n(tRoewsni,d eLnotniga lB rLainscthi,n gA sAbgurreye mPeanrtk,,  LReeadd  BPaanikn,t  FDriesechloolsdu,r eH,o wCeolnls,u mMearn aIlnafpoarnm,a tMiaornl bSotraot,e mHeonltm,d ealn,d  MSiedldlleert oPwrno,p eHratzyl eCto
          nOdcietaino:n  TDoimssc lRoisvuerre,)  Lwaiktehw opordo,p eBrrtiyc ka,d dJraecskss,o ns,e lMlaenrc hiensftoe,r ,a nBda rJneengiaste,' sP oaignetn tP ldeeatsaainlts
          .S
          o m e-r sMeAtN:D AFTrOaRnYk lTiRnI,G GBErRiSd:g elwiastteirn,g  Hfiolrlmssb,o rfoiulglh ,f oMramnsv,i lllies,t iBnogu nadp pBorionotkm,e nSto,m elrivsitlilneg

           p#a#p eOruwtoprukt,
            Sfaivlel  toou to ultipsuttisn:g  Raegsriedeemnetnita,l _lLeiasdt ipnagi_nAtg rfeoermme,n tp_r[oApdedrrteys sd]i.spcdlfo,s uLreea df_oPrami,n tc_oDnissucmleors uirnef_o[rAmdadtrieosns ]s.tpadtfe,m eCnotn,s ulmiesrt_iInngf opramcakteito,n _pSrteaptaermee nfto_r[mAsd,d rneesws ]l.ipsdtfi,n gS,e lflielrl_ Ptrhoep efrotrym_sD,i sccolmopsluertee_ [tAhded rfeosrsm]s.,p dlfisting docs
              - Also trigger when Jenise mentions going on a listing appointment, preparing paperwork for a listing, or needing forms filled for a new property/seller
                - This skill requires the 4 blank template PDFs to be uploaded or available in the uploads foldern 7(c)

                ### 2. Lead Paint Disclosure (8/16)
                Check: Seller has no knowledge, Seller has no reports. Listing Agent = Jenise Buckalew. Leave purchaser sections blank.

                ### 3. Consumer Information Statement (CIS)
                Page 2 For Sellers: Licensee name = Jenise Buckalew. Leave signature/date blank.

                ### 4. Seller Property Condition Disclosure (Form 140)
                Page 2: Seller names only. Leave ALL questions blank for seller to complete.

                ## Key Coordinates (PDF coords, y=0 at top, pdf_width: 612, pdf_height: 792)

                Listing Page 1: Seller names [131,224,430,236], Address [183,246,565,258], County [478,378,565,390], Exclusive broker [215,411,226,422], Seller Agent [47,510,56,521], Dual Agent [47,532,56,543], Designated [47,554,56,565]

                Listing Page 2: MLS [420,127,565,139], Commission exclusive [409,622,530,634], non-exclusive [82,678,200,690]

                Listing Page 3: Commission regardless [202,92,330,104]

                Listing Page 4: Split amount [429,236,535,248], Auth splits [83,358,94,369], Sub Yes [274,468,285,479], Sub offer [340,468,385,480], Buyers Yes [274,485,285,496], Buyers offer [340,485,385,497], Trans Yes [274,502,285,513], Trans offer [340,502,385,514], Auth disclose [83,535,94,546]

                Lead Paint Page 1: No knowledge [68,393,95,405], No reports [68,432,95,444], Agent name [107,667,460,679]

                CIS Page 2: Licensee name [73,555,210,567]

                Disclosure Page 2: Seller names [80,143,565,155]

                ## NJ County Lookup
                Middlesex: Sayreville, Old Bridge, East Brunswick, Edison, Woodbridge, Perth Amboy, New Brunswick, Piscataway, Monroe Township
                Monmouth: Eatontown, Long Branch, Asbury Park, Red Bank, Freehold, Howell, Manalapan, Marlboro, Holmdel, Middletown, Hazlet
                Ocean: Toms River, Lakewood, Brick, Jackson, Manchester, Barnegat, Point Pleasant
                Somerset: Franklin, Bridgewater, Hillsborough, Manville, Bound Brook, Somerville

                ## Output
                Save to outputs: Residential_Listing_Agreement_[Address].pdf, Lead_Paint_Disclosure_[Address].pdf, Consumer_Information_Statement_[Address].pdf, Seller_Property_Disclosure_[Address].pdf
                ---

                # Listing Appointment Forms Filler

                This skill fills out the 4 standard NJ listing appointment forms for Jenise Buckalew at Green Light Realty LLC.

                ## Required Information

                At minimum: Property address and Seller name(s)

                Optional (defaults): Commission rate (5%), MLS fee ($200), Cooperating broker commission (2%), County (auto from city), Seller phone/email, Listing price, Block/Lot numbers

                ## Agent Info (Pre-filled)
                - Agent: Jenise Buckalew, REALTOR
                - Brokerage: Green Light Realty LLC
                - Office: 1109 Englishtown Rd, Old Bridge, NJ 08857
                - Phone: (347) 393-5993
                - Email: jenisesellsnj@gmail.com

                ## The 4 Forms

                ### 1. Residential Listing Agreement (Form 150)
                Fill: Seller names, Primary Address, County, exclusive broker checkbox, all 3 agency checkboxes, MLS fee (Section 4), Commission % in Section 5(a)(i/ii/iii), Commission split on page 4, authorize splits checkbox Section 7(a), Section 7(b) table Yes/offer for Subagents/Buyers Brokers/Transaction Brokers under Sale, authorize disclosure Sectio
