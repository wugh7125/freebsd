# $FreeBSD$

TESTSDIR=	${TESTSBASE}/sys/auditpipe

ATF_TESTS_C=	auditpipe_test

TEST_METADATA+= required_user="root"
TEST_METADATA+= required_files="/dev/auditpipe"
WARNS?=	6

.include <bsd.test.mk>
