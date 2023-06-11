.. _award_calculation:

Award Calculation
=================

The award calculation for dealers involves a systematic process of evaluating their performance and determining the recipients of recognition and rewards. This process incorporates various metrics and criteria, such as sales growth, customer satisfaction ratings, marketing efforts, and adherence to company policies. The calculation takes into account quantitative and qualitative factors to ensure a fair and comprehensive assessment. By accurately calculating awards, companies can motivate dealers to strive for excellence, foster healthy competition, and drive business growth. The award calculation serves as a powerful tool for acknowledging the outstanding achievements of dealers and reinforcing their commitment to success.

Reference:
----------

Link: https://bml-dev.outsystemsenterprise.com/DealerMargins/AwardCalculation

Web View:

.. image:: images/Screens/Award_Calculation/award_calculation.png
   :width: 600

Screen Actions:

.. image:: images/Screens/Award_Calculation/Screen_Actions.png
   :width: 400

Variables:

.. image:: images/Screens/Award_Calculation/Screen_Variable.png
   :width: 400

Data Source:

.. image:: images/Screens/Award_Calculation/Screen_Data.png
   :width: 400

Calculation Flow:
-----------------

#. The calculation is initiated by selecting the 'CalculateOnClick' screen action.

.. image:: images/Screens/Award_Calculation/CalculateOnClick.png
   :width: 600

* The preceding step invokes the "Initiate Calculation" action, which creates an initial entry in the **Regional Payment Calculation** entity for either Primary or Retro entries.
* Subsequently, the following actions are triggered:
    #. Validate Process (Initiate Process)
        * Consecutive Period Valdation
        * Plan Configuratio Validation
        * Wholesale Data Validation
    #. Process Primary Calculation (Process Calculation)
        * Default Dealer Component Award
        * VIN Level Guarantee (VIN Monetory)
        * VIN Level Component Awards (VIN Award By Component)
        * Dealer Transfers (Transfer Adjustment)
    #. Process Retro Calculation (if Any) (Process Retro Calculation)
        * Retro Default Dealer Component Award
        * Retro VIN Level Guarantee (VIN Monetory)
        * Retro VIN Level Component Awards (VIN Award By Component)
        * Retro Dealer Transfers (Transfer Adjustment)

Initiate Calculation
--------------------

.. image:: images/Screens/Award_Calculation/InitiateCalculation.png
    :width: 600

Initiate Process
----------------

.. image:: images/Screens/Award_Calculation/ValidateConsecutivePeriod.png
    :width: 600

Consecutive Period Valdation
----------------------------

.. image:: images/Screens/Award_Calculation/ValidateConsecutivePeriod.png
    :width: 600

Plan Configuratio Validation
----------------------------

.. image:: images/Screens/Award_Calculation/ValidatePlanConfiguration.png
    :width: 600

Wholesale Data Validation
-------------------------

.. image:: images/Screens/Award_Calculation/ValidateWholesaleData.png
    :width: 600

Process Calculation
-------------------

.. image:: images/Screens/Award_Calculation/ProcessCalculation.png
    :width: 600

Default Dealer Component Award
------------------------------

.. image:: images/Screens/Award_Calculation/CalculateDefaultDealerAward.png
    :width: 600

Component Level Award & VIN Component Level Award
-------------------------------------------------

.. image:: images/Screens/Award_Calculation/ComponentLevelAward.png
    :width: 600

VIN Level Guarantee (VIN Monetory)
----------------------------------

.. image:: images/Screens/Award_Calculation/CalculateVINMonetoryGuarantees.png
    :width: 600

VIN Level Component Awards (VIN Award By Component)
---------------------------------------------------

.. image:: images/Screens/Award_Calculation/CalculateVINLevelComponentAward.png
    :width: 600

Dealer Transfers (Transfer Adjustment)
--------------------------------------

.. image:: images/Screens/Award_Calculation/CalculateTransferAdjustment.png
    :width: 600

Retor Process Calculation
-------------------------

.. image:: images/Screens/Award_Calculation/ProcessRetroCalculation.png
    :width: 600

Retro Default Dealer Component Award
------------------------------------

.. image:: images/Screens/Award_Calculation/Retro_CalculateDefaultDealerAward.png
    :width: 600

Retro VIN Level Guarantee (VIN Monetory)
----------------------------------------

.. image:: images/Screens/Award_Calculation/Retro_CalculateVINMonetoryGuarentee.png
    :width: 600

Retro VIN Level Component Awards (VIN Award By Component)
---------------------------------------------------------

.. image:: images/Screens/Award_Calculation/Retro_CalculateVINLevelComponentAward.png
    :width: 600

Retro Dealer Transfers (Transfer Adjustment)
--------------------------------------------

.. image:: images/Screens/Award_Calculation/Retro_CalculateTransferAdjustment.png
    :width: 600

