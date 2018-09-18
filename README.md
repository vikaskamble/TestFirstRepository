# TestFirstRepository
Test First Repository

@Test(priority = 0, description = "Get Twitter Time Line data...")
	public void getTwitterTimeLine() throws TwitterException{
		logger = extentReports.createTest("Get Twitter Time Line data.");
		logger.log(Status.INFO, "This test case display twitter home page time line data.");
		new TwitterPOC_Action(logger).getTwitter_TimeLineData();		 
		//logger.log(Status.PASS, Thread.currentThread().getStackTrace()[1].getMethodName()+"  Test Case Pass");
	}
