?   !SPYLeaveApplication_MyApplicationVa5    ?  SPYMyTeamMemberVa5?  �   SPYPayrollJournalQueryVa5�  �   SPYHcmWorkerLookup_ActiveVa5�  �  SPYOvertimeJournalVa5A  �   "SPYMyTeamMember_CurrentLegalEntityVa5�  !  SPYLeaveApplicationWFQueryVa5�  �   SPYAbsenceJournalQueryVa5�  �   SPYOvertimeJournal_MyJournalVa5h  �   SPYPayLoanWFQueryVa5F  �   %SPYLeaveApplication_MyEmplApplicationVa5�  �  SPYWorkerAbsenceCodeLookupVa5�
  �  SPYPayElementVa5~    SPYPayArrearQueryVa5�  �  SPYPayrollPeriodLookupVa5�    SPYOvertimeLedgerVa5�  ?  SPYBenefitJournalWFQueryVa5�  �   SPYEOSRunReportQueryVa5�  �  SPYDocumentRequest_MyRequestVa5�  �   !SPYOvertimeJournalWorkflowHistoryVa5�  �  SPYPayLoanListPagePreviewPaneVa5�  �   SPYDocumentRequestVa5.   �    SPYPayrollJournalWorkflowHistoryVa5�   �   SPYPayrollEarningsJournalWFQueryVa5�"  �   SPYSubordinatesLookupVa5�#  X  SPYLeaveApplicationSRSVa5�$  |  SPYPayLoanQueryVa5f&  �   SPYDocumentRequestWFQueryVa5'  �   SPYSubordinateLookupVa5�'  `  SPYLeaveDetailsVa5")  �  SPYOvertimeJournalWFQueryVa5�,  �   SPYCompensationPlanQueryVa5u-  �   SPYWorkerHierarchyVa5.  "  SPYEOSHcmWorkerLookupVa5./  �    SPYBenefitJournalWorkflowHistoryVa5 0  �  "SPYLeaveApplicationWorkflowHistoryVa52  �  SPYEOSRunWFQueryVa5�3  k    SPYAbsenceJournalWorkflowHistoryVa5g4  �  !SPYOvertimeJournalListPagePreviewVa5T6  �   SPYDisbursementJourTableQueryVa567  �   SPYLeaveApplicationVa58  �   SPYLeaveApplicationSettlementVa5�8  \   SPYDocumentRequest_MYTeamRequestVa57<  �   SPYPayLoanRecoveryVa5�<  �  SPYPayAdjustmentQueryVa5�?  �   
SPYPayLoanVa5�@  g   &SPYLeaveApplicationListPagePreviewPaneVa5!A  �   SPYHcmWorkerNoPositionVa5�A  \   SPYPromotionTableWFQueryVa5WB  n   SPYSalaryRegisterDetailsVa5�B  �   SPYPayLoanSRSVa5GC  �   	SPYEOSRunVa5D    SPYPayrollEarningsJournalQueryVa5E  �   %SPYDocumentRequestListPagePreviewPaneVa5
F  �   (SPYPayrollEarningsJournalWorkflowHistoryVa5�F  �  SPYHcmWorkerEmploymentVa5�H  �   SPYPayLoan_MyLoanVa5SI  �   %SPYLeaveApplication_MyTeamApplicationVa5J  �  SPYPayAdjustmentWFQueryVa5L  �   SPYOvertimeJournalQueryVa5�L  �   SPYPayrollJournalWFQueryVa5�M  �   SPYBenefitJournalQueryVa5hN  �   SPYBenefitQueryVa5,O  �   � )   8 SPYLeaveApplicationTable_1   7SPYLeaveApplicationTable_1 LeaveApplicationCodeLeaveApplicationCode�   1WorkerWorker ?((Worker = HcmWorkerLookup::currentWorker()) && ( Worker != 0))�SPYLeaveApplicationTable�
   � 
classDeclaration� ��!SPYLeaveApplication_MyApplication@SPY695�� )   8   4 SPYMyTeamMemberSPYMyTeamMember � 	HcmWorker	HcmWorker�
   � 
classDeclaration� ��SPYMyTeamMember�� )   8   4  SPYPayrollJournalLine_1SPYPayrollJournalLine � SPYPayrollJournalTable_1SPYPayrollJournalTable�
   � 
classDeclaration� ��SPYPayrollJournalQuery@SPY322�� )   8   4 	DirPerson   2	HcmWorker	DirPersonRelation�	DirPerson �4  HcmEmployment   1LegalEntityLegalEntity�1WorkerWorker�1ValidToValidTo�1	ValidFrom	ValidFrom�1EmploymentTypeEmploymentType�   2	HcmWorker	HcmWorkerRelation�HcmEmployment � 	HcmWorker   7	HcmWorkerPersonnelNumberQueryOrderByField1�	HcmWorker�
   � 
classDeclaration� ��SPYHcmWorkerLookup_Active�� )   8 SPYOvertimeJournalTable_1SPYOvertimeJournalTable�
   � 
classDeclaration� ��SPYOvertimeJournalOvertime journal�� )   8	   +LegalEntityLegalEntity�+
TeamMember
TeamMember�SPYMyTeamMember   1
TeamMember
TeamMember0(TeamMember != HcmWorkerLookup::currentWorker())�SPYMyTeamMember�
   � 
classDeclaration� ��"SPYMyTeamMember_CurrentLegalEntity@SPY:MyTeamMemberCurrentCompany�� )   8   4 SPYLeaveApplicationLine_1SPYLeaveApplicationLine �4 	HcmWorker	HcmWorker � SPYLeaveApplicationTable_1SPYLeaveApplicationTable�
   � 
classDeclaration� ��� 
init�  � �SPYLeaveApplicationWFQuery@SPY712�� )   8 SPYAbsenceJournalTable_1SPYAbsenceJournalTable�
   � 
classDeclaration� ��SPYAbsenceJournalQuery@SPY1587�� )   8 SPYOvertimeJournalTable_1   1	createdBy	createdBy4((createdBy = currentUserId()) && ( createdBy != 0))�SPYOvertimeJournalTable�
   � 
classDeclaration� ��SPYOvertimeJournal_MyJournal@SPY1051�� )   8   4 SPYPayLoanLine_1SPYPayLoanLine � SPYPayLoanTable_1SPYPayLoanTable�
   � 
classDeclaration� ��SPYPayLoanWFQuery@SPY354�� )   8   4 SPYMYSubordinate   2WorkerSPYLeaveApplicationTable_1QueryDataSourceRelation1Worker�SPYMYSubordinate� SPYLeaveApplicationTable_1   7SPYLeaveApplicationTable_1 LeaveApplicationCodeLeaveApplicationCode�   1WorkerWorker-( Worker != HcmWorkerLookup::currentWorker())�SPYLeaveApplicationTable�
   � 
classDeclaration� ��%SPYLeaveApplication_MyEmplApplication@SPY695�� )   8   4 "SPYWorkerPositionAbsenceConfigLine"SPYWorkerPositionAbsenceConfigLine �	'   +HRMAbsenceCodebackgroundColorbackgroundColor�+HRMAbsenceCode
dataAreaId
dataAreaId�+HRMAbsenceCodeDefaultDimensionDefaultDimension�+HRMAbsenceCodedescriptiondescription�+HRMAbsenceCode	foreColor	foreColor�+HRMAbsenceCodehrmAbsenceCodeGroupIdhrmAbsenceCodeGroupId�+HRMAbsenceCodehrmAbsenceCodeIdhrmAbsenceCodeId�+HRMAbsenceCodeJmgAbsenceLetterCodeJmgAbsenceLetterCode�+HRMAbsenceCodeJmgAbsenceMethodEnumJmgAbsenceMethodEnum�+HRMAbsenceCodeJmgAbsencePayCTypeJmgAbsencePayCType�+HRMAbsenceCodeJmgAbsencePayQtyJmgAbsencePayQty�+HRMAbsenceCodeJmgColIndexJmgColIndex�+HRMAbsenceCodeJmgContinousAbsenceJmgContinousAbsence�+HRMAbsenceCode	jmgIconId	jmgIconId�+HRMAbsenceCodeJmgIncludeInReportJmgIncludeInReport�+HRMAbsenceCodeJmgJobIdJmgJobId�+HRMAbsenceCode	JmgSignIn	JmgSignIn�+HRMAbsenceCodeLedgerDimensionLedgerDimension�+HRMAbsenceCodemaxDaysPeriodmaxDaysPeriod�+HRMAbsenceCodemaxDaysPeriodActivemaxDaysPeriodActive�+HRMAbsenceCodemaxDaysPeriodCodemaxDaysPeriodCode�+HRMAbsenceCodemaxDaysPeriodQtymaxDaysPeriodQty�+HRMAbsenceCode
maxInSerie
maxInSerie�+HRMAbsenceCodemaxInSerieActivemaxInSerieActive�+HRMAbsenceCodemaxInSeriePeriodCodemaxInSeriePeriodCode�+HRMAbsenceCodemaxInSeriePeriodQtymaxInSeriePeriodQty�+HRMAbsenceCodemaxInSerieWorkingdaysmaxInSerieWorkingdays�+HRMAbsenceCodemaxSeriesPeriodmaxSeriesPeriod�+HRMAbsenceCodemaxSeriesPeriodActivemaxSeriesPeriodActive�+HRMAbsenceCodemaxSeriesPeriodCodemaxSeriesPeriodCode�+HRMAbsenceCodemaxSeriesPeriodQtymaxSeriesPeriodQty�+HRMAbsenceCodemaxSeriesPeriodWorkingdaysmaxSeriesPeriodWorkingdays�+HRMAbsenceCodeOffsetLedgerDimensionOffsetLedgerDimension�+HRMAbsenceCode	Partition	Partition�+HRMAbsenceCodeRecIdRecId�+HRMAbsenceCode
recVersion
recVersion�+HRMAbsenceCodeSPYBalanceValidationSPYBalanceValidation�+HRMAbsenceCode
SPYBenefit
SPYBenefit�+HRMAbsenceCodeSPYIsUnpaidSPYIsUnpaid�HRMAbsenceCode_1HRMAbsenceCode�
   � 
classDeclaration� ��SPYWorkerAbsenceCodeLookup�� )   8   4 SPYPayElementDetails_1SPYPayElementDetails �    5SPYPayElementTable_1RecIdRecId�5SPYPayElementTable_1PayElementTypePayElementType�SPYPayElementTable_1   7SPYPayElementTable_1PayElementCodePayElementCode�7SPYPayElementTable_1PayElementTypePayElementType�SPYPayElementTable�
   � 
classDeclaration� ��SPYPayElement�� )   8   4   4 SPYPayrollPeriodLine_1   1PeriodStartDatePeriodStartDate"(PeriodStartDate <= currentDate())�1PeriodEndDatePeriodEndDate (PeriodEndDate >= currentDate())�SPYPayrollPeriodLine �   SPYWorkerPayrollPeriodFinalize_1SPYWorkerPayrollPeriodFinalize �4  HcmEmployment_1HcmEmployment � HcmWorker_1	HcmWorker�
   � 
classDeclaration� ��SPYPayArrearQuery�� )   8   4 SPYPayrollPeriodLine_1   1PeriodStatusPeriodStatus0�SPYPayrollPeriodLine � SPYPayrollPeriod_1   7SPYPayrollPeriodLine_1 PeriodStartDatePeriodStartDate�SPYPayrollPeriod�
   � 
classDeclaration� ��SPYPayrollPeriodLookup�� )   8   4   4 	HcmWorker   1PersonnelNumberPersonnelNumber�	HcmWorker � SPYOvertimeLedger   1OvertimeDateOvertimeDate�SPYOvertimeLedger � SPYOvertimeTypeTable   1OvertimeTypeCodeOvertimeTypeCode�SPYOvertimeTypeTable�
   � 
classDeclaration� ��SPYOvertimeLedger�� )   8   4 SPYBenefitJournalTrans_1SPYBenefitJournalTrans � SPYBenefitJournalTable_1SPYBenefitJournalTable�
   � 
classDeclaration� ��SPYBenefitJournalWFQuery�� )   8	   +SPYEOSRunTable	createdBy	createdBy�+SPYEOSRunTablecreatedDateTimecreatedDateTime�+SPYEOSRunTable
dataAreaId
dataAreaId�+SPYEOSRunTableEOSDateEOSDate�+SPYEOSRunTable
modifiedBy
modifiedBy�+SPYEOSRunTablemodifiedDateTimemodifiedDateTime�+SPYEOSRunTable	Partition	Partition�+SPYEOSRunTablePostedToLedgerPostedToLedger�+SPYEOSRunTableRecIdRecId�+SPYEOSRunTable
recVersion
recVersion�+SPYEOSRunTableRemarksRemarks�+SPYEOSRunTable	TransDate	TransDate�+SPYEOSRunTableWorkerWorker�+SPYEOSRunTableWorkflowStatusWorkflowStatus�+SPYEOSRunTableRecIdRecId_1�SPYEOSRunTable_1SPYEOSRunTable�
   � 
classDeclaration� ��SPYEOSRunReportQueryEos run query�� )   8 SPYDocumentRequestTable_1   1WorkerWorker?((Worker = HcmWorkerLookup::currentWorker()) && ( Worker != 0))�SPYDocumentRequestTable�
   � 
classDeclaration� ��SPYDocumentRequest_MyRequest@SPY:HRRequestQuery�� )   8   4   4 WorkflowTrackingStatusTableWorkflowTrackingStatusTable �WorkflowTrackingTableWorkflowTrackingTable � WorkflowTrackingCommentTable   7WorkflowTrackingTable CreatedDateTimeQueryOrderByField1�7WorkflowTrackingStatusTable CreatedDateTimeQueryOrderByField2�7WorkflowTrackingCommentTable RecIdQueryOrderByField3�WorkflowTrackingCommentTable�
   � 
classDeclaration� ��� 
init�  � �!SPYOvertimeJournalWorkflowHistory�� )   8   4  SPYPayLoanLine_1SPYPayLoanLine � SPYPayLoanTable_1SPYPayLoanTable�
   � 
classDeclaration� ��SPYPayLoanListPagePreviewPane@SPY354�� )   8 SPYDocumentRequestTable_1SPYDocumentRequestTable�
   � 
classDeclaration� ��SPYDocumentRequest@SPY:HRRequestQuery�� )   8   4   4 WorkflowTrackingStatusTableWorkflowTrackingStatusTable �WorkflowTrackingTableWorkflowTrackingTable � WorkflowTrackingCommentTable   7WorkflowTrackingTable CreatedDateTimeQueryOrderByField1�7WorkflowTrackingStatusTable CreatedDateTimeQueryOrderByField2�7WorkflowTrackingCommentTable RecIdQueryOrderByField3�WorkflowTrackingCommentTable�
   � 
classDeclaration� ��� 
init�  � � SPYPayrollJournalWorkflowHistory�� )   8   4  SPYPayrollEarningsJournalTrans_1SPYPayrollEarningsJournalTrans �  SPYPayrollEarningsJournalTable_1SPYPayrollEarningsJournalTable�
   � 
classDeclaration� �� SPYPayrollEarningsJournalWFQuery@SPY1206�� )   8   4 SPYMYSubordinate   2RecId	HcmWorkerRecIdWorker�SPYMYSubordinate�	   +	HcmWorkerPersonnelNumberPersonnelNumber�+	HcmWorkerPersonPerson�+	HcmWorkerRecIdRecId�	HcmWorker   1RecIdRecId!=HcmWorkerLookup::currentWorker()�	HcmWorker�
   � 
classDeclaration� ��SPYSubordinatesLookup�� )   8   4   4 	DirPerson	DirPerson � 	HcmWorker	HcmWorker �4 SPYLeaveApplicationLine   1HRMAbsenceCodeHRMAbsenceCode�SPYLeaveApplicationLine � SPYLeaveApplicationTable   1LeaveApplicationCodeLeaveApplicationCode�1WorkflowStatusWorkflowStatus�SPYLeaveApplicationTable�
   � 
classDeclaration� ��SPYLeaveApplicationSRS�� )   8   4  SPYPayLoanLine_1SPYPayLoanLine � SPYPayLoanTable_1SPYPayLoanTable�
   � 
classDeclaration� ��SPYPayLoanQuery@SPY354�� )   8   4 SPYDocumentRequestLine_1SPYDocumentRequestLine � SPYDocumentRequestTable_1SPYDocumentRequestTable�
   � 
classDeclaration� ��SPYDocumentRequestWFQuery�� )   8   4   4 HcmPositionDetail   1
Department
Department�   2PositionHcmPositionWorkerAssignmentPositionPosition�HcmPositionDetail� HcmPositionWorkerAssignmentHcmPositionWorkerAssignment � 	HcmWorker   1PersonnelNumberPersonnelNumber�	HcmWorker�
   � 
classDeclaration� ��SPYSubordinateLookup�� )   8   4
   +SPYPayElementTablePayElementCodePayElementCode�+SPYPayElementTablePayElementTypePayElementType�SPYPayElementTable_1SPYPayElementTable �4
   +SPYPayrollPeriodLinePayrollPeriodPayrollPeriod�+SPYPayrollPeriodLinePeriodStartDatePeriodStartDate�+SPYPayrollPeriodLinePeriodEndDatePeriodEndDate�SPYPayrollPeriodLine_1SPYPayrollPeriodLine �4 HcmWorker_1	HcmWorker �	   +SPYBenefitLedgerJournalTypeJournalType�+SPYBenefitLedger	TransDate	TransDate�+SPYBenefitLedgerQuantityQuantity�+SPYBenefitLedgerAccountingCurrencyAmountAccountingCurrencyAmount�+SPYBenefitLedgerAccountingCurPnLAmountAccountingCurPnLAmount�+SPYBenefitLedgerBenefitBenefit�SPYBenefitLedgerSPYBenefitLedger�$Leave accrual and encashment details
   � 
classDeclaration� ��SPYLeaveDetails$Leave accrual and encashment details�� )   8   4 SPYOvertimeJournalTrans_1SPYOvertimeJournalTrans � SPYOvertimeJournalTable_1SPYOvertimeJournalTable�
   � 
classDeclaration� ��SPYOvertimeJournalWFQuery�� )   8 SPYCompensationPlanTable_1SPYCompensationPlanTable�Compensation plan query
   � 
classDeclaration� ��SPYCompensationPlanQuery�� )   8   4   4 HcmPositionHierarchy_1   2PositionHcmPositionWorkerAssignment_1PositionPosition�HcmPositionHierarchy� HcmPositionWorkerAssignment_1HcmPositionWorkerAssignment � HcmWorker_1	HcmWorker�
   � 
classDeclaration� ��SPYWorkerHierarchy�� )   8   4 	DirPerson	DirPerson �4  HcmPersonImage   2Person	HcmWorkerPersonPerson�HcmPersonImage� 	HcmWorker   7	DirPersonNameName�	HcmWorker�
   � 
classDeclaration� ��SPYEOSHcmWorkerLookup�� )   8   4   4 WorkflowTrackingStatusTableWorkflowTrackingStatusTable �WorkflowTrackingTableWorkflowTrackingTable � WorkflowTrackingCommentTable   7WorkflowTrackingTable CreatedDateTimeQueryOrderByField1�7WorkflowTrackingStatusTable CreatedDateTimeQueryOrderByField2�7WorkflowTrackingCommentTable RecIdQueryOrderByField3�WorkflowTrackingCommentTable�
   � 
classDeclaration� ��� 
init�  � � SPYBenefitJournalWorkflowHistory�� )   8   4   4 WorkflowTrackingStatusTableWorkflowTrackingStatusTable �WorkflowTrackingTableWorkflowTrackingTable � WorkflowTrackingCommentTable   7WorkflowTrackingTable CreatedDateTimeQueryOrderByField1�7WorkflowTrackingStatusTable CreatedDateTimeQueryOrderByField2�7WorkflowTrackingCommentTable RecIdQueryOrderByField3�WorkflowTrackingCommentTable�
   � 
classDeclaration� ��� 
init�  � �"SPYLeaveApplicationWorkflowHistory�� )   8 SPYEOSRunTable_1SPYEOSRunTable�
   � 
classDeclaration� ��SPYEOSRunWFQuery@SPY680�� )   8   4   4 WorkflowTrackingStatusTableWorkflowTrackingStatusTable �WorkflowTrackingTableWorkflowTrackingTable � WorkflowTrackingCommentTable   7WorkflowTrackingTable CreatedDateTimeQueryOrderByField1�7WorkflowTrackingStatusTable CreatedDateTimeQueryOrderByField2�7WorkflowTrackingCommentTable RecIdQueryOrderByField3�WorkflowTrackingCommentTable�
   � 
classDeclaration� ��� 
init�  � � SPYAbsenceJournalWorkflowHistory�� )   8   4  SPYOvertimeJournalTrans_1SPYOvertimeJournalTrans � SPYOvertimeJournalTable_1SPYOvertimeJournalTable�
   � 
classDeclaration� ��!SPYOvertimeJournalListPagePreviewOvertime journal query�� )   8   4  SPYDisbursementJournalLineSPYDisbursementJournalLine � SPYDisbursementJournalTableSPYDisbursementJournalTable�
   � 
classDeclaration� ��SPYDisbursementJourTableQuery�� )   8 SPYLeaveApplicationTable_1   7SPYLeaveApplicationTable_1 LeaveApplicationCodeLeaveApplicationCode�SPYLeaveApplicationTable�
   � 
classDeclaration� ��SPYLeaveApplication@SPY712�� )   8   4   4   4  SPYBenefitTable_1SPYBenefitTable �  HRMAbsenceCode_1HRMAbsenceCode � SPYLeaveApplicationLine_1SPYLeaveApplicationLine �4   4   4 SPYPayrollJournalTable_1   1PostedPosted Yes�SPYPayrollJournalTable � SPYPayrollJournalLine_1SPYPayrollJournalLine � SPYPayrollLedger_1SPYPayrollLedger �4   4   4 SPYPayrollJournalTable_1_1   1PostedPosted Yes�SPYPayrollJournalTable � SPYPayrollJournalLine_1_1SPYPayrollJournalLine � SPYBenefitLedger_1SPYBenefitLedger � SPYLeaveApplicationTable_1   7SPYLeaveApplicationTable_1 LeaveApplicationCodeLeaveApplicationCode�   1WorkflowStatusWorkflowStatus Approved�SPYLeaveApplicationTable�
   � 
classDeclaration� ��SPYLeaveApplicationSettlement@SPY712�� )   8 SPYDocumentRequestTable_1SPYDocumentRequestTable�
   � 
classDeclaration� �� SPYDocumentRequest_MYTeamRequest@SPY:HRRequestQuery�� )   8   4   4   4   4
   +SPYPayrollJournalTablePostedPosted� SPYPayrollJournalTable_1   1PostedPostedYes�SPYPayrollJournalTable � SPYPayrollJournalLine_1SPYPayrollJournalLine �
   0SPYPayrollLedgerAccountingCurrencyAmountAccountingCurrencyAmount�0SPYPayrollLedgerTransactionCurrencyAmountTransactionCurrencyAmount� SPYPayrollLedger_1   2PayLedgerSourceSPYPayLedgerSourceLine_1PayLedgerSourcePayLedgerSource�SPYPayrollLedger�  SPYPayLedgerSourceLine_1   1TableReferenceTableReference103111�   2RecIdSPYPayLoanLedger_1RecIdRecordReference�SPYPayLedgerSourceLine� SPYPayLoanLedger_1SPYPayLoanLedger�
   � 
classDeclaration� ��SPYPayLoanRecovery�� )   8   4  SPYPayAdjustmentTrans_1SPYPayAdjustmentTrans � SPYPayAdjustmentTable_1   1PayAdjustmentCodePayAdjustmentCode�SPYPayAdjustmentTable�
   � 
classDeclaration� ��SPYPayAdjustmentQuery@SPY276�� )   8 SPYPayLoanTable_1SPYPayLoanTable�
   � 
classDeclaration� ��
SPYPayLoan@SPY354�� )   8   4  SPYLeaveApplicationLine_1SPYLeaveApplicationLine � SPYLeaveApplicationTable_1SPYLeaveApplicationTable�
   � 
classDeclaration� ��&SPYLeaveApplicationListPagePreviewPane@SPY712�� )   8 	HcmWorker	HcmWorker�
   � 
classDeclaration� ��SPYHcmWorkerNoPosition�� )   8 SPYPromotionTableSPYPromotionTable�
   � 
classDeclaration� ��SPYPromotionTableWFQuery�� )   8 SPYSalaryRegisterDetailsTmpSPYSalaryRegisterDetailsTmp�
   � 
classDeclaration� ��SPYSalaryRegisterDetails�� )   8   4 SPYPayLoanLineSPYPayLoanLine �4   4 	DirPerson	DirPerson � 	HcmWorker	HcmWorker � SPYPayLoanTableSPYPayLoanTable�
   � 
classDeclaration� ��SPYPayLoanSRS�� )   8   4  SPYEOSRunPayroll_1SPYEOSRunPayroll�4  SPYEOSRunBenefit_1SPYEOSRunBenefit� SPYEOSRunTable_1   7SPYEOSRunTable_1 createdDateTimecreatedDateTime�SPYEOSRunTable�
   � 
classDeclaration� ��	SPYEOSRun@SPY655�� )   8   4   SPYPayrollEarningsJournalTrans_1SPYPayrollEarningsJournalTrans �  SPYPayrollEarningsJournalTable_1SPYPayrollEarningsJournalTable�
   � 
classDeclaration� ��SPYPayrollEarningsJournalQuery@SPY1206�� )   8   4  SPYDocumentRequestLine_1SPYDocumentRequestLine � SPYDocumentRequestTable_1SPYDocumentRequestTable�
   � 
classDeclaration� ��%SPYDocumentRequestListPagePreviewPane�� )   8   4   4 WorkflowTrackingStatusTableWorkflowTrackingStatusTable �WorkflowTrackingTableWorkflowTrackingTable � WorkflowTrackingCommentTable   7WorkflowTrackingTable CreatedDateTimeQueryOrderByField1�7WorkflowTrackingStatusTable CreatedDateTimeQueryOrderByField2�7WorkflowTrackingCommentTable RecIdQueryOrderByField3�WorkflowTrackingCommentTable�
   � 
classDeclaration� ��� 
init�  � �(SPYPayrollEarningsJournalWorkflowHistory�� )   8   4 HcmEmploymentHcmEmployment � 	HcmWorker	HcmWorker�
   � 
classDeclaration� ��SPYHcmWorkerEmployment�� )   8 SPYPayLoanTable_1   1WorkerWorker?((Worker = HcmWorkerLookup::currentWorker()) && ( Worker != 0))�SPYPayLoanTable�
   � 
classDeclaration� ��SPYPayLoan_MyLoan@SPY713�� )   8   4
   +LegalEntityLegalEntity�+
TeamMember
TeamMember�SPYMyTeamMember   1LegalEntityLegalEntityRangeCompanyInfo::current()�   2WorkerSPYLeaveApplicationTable_1QueryDataSourceRelation1
TeamMember�SPYMyTeamMember� SPYLeaveApplicationTable_1   7SPYLeaveApplicationTable_1 LeaveApplicationCodeLeaveApplicationCode�   1WorkerWorker�SPYLeaveApplicationTable�
   � 
classDeclaration� ��%SPYLeaveApplication_MyTeamApplication@SPY695�� )   8   4 SPYPayAdjustmentTrans_1SPYPayAdjustmentTrans � SPYPayAdjustmentTable_1SPYPayAdjustmentTable�
   � 
classDeclaration� ��SPYPayAdjustmentWFQuery@SPY276�� )   8   4  SPYOvertimeJournalTrans_1SPYOvertimeJournalTrans � SPYOvertimeJournalTable_1SPYOvertimeJournalTable�
   � 
classDeclaration� ��SPYOvertimeJournalQueryOvertime journal query�� )   8   4 SPYPayrollJournalLine_1SPYPayrollJournalLine � SPYPayrollJournalTable_1SPYPayrollJournalTable�
   � 
classDeclaration� ��SPYPayrollJournalWFQuery@SPY322�� )   8   4  SPYBenefitJournalTrans_1SPYBenefitJournalTrans � SPYBenefitJournalTable_1SPYBenefitJournalTable�
   � 
classDeclaration� ��SPYBenefitJournalQuery@SPY404�� )   8   4 SPYBenefitDetails_1   1LegalEntityLegalEntity$(LegalEntity = currentLegalEntity())�SPYBenefitDetails � SPYBenefitTable_1SPYBenefitTable�
   � 
classDeclaration� ��SPYBenefitQuery�