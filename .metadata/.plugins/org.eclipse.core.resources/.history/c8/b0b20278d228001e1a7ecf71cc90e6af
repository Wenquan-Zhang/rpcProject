package com.xtwy.pro_netty_rpc;

import org.junit.Test;

import com.xtwy.netty.client.ClientRequest;
import com.xtwy.netty.client.Response;
import com.xtwy.netty.client.TcpClient;

public class TestTcp {

	@Test
	public void testGetResponse() {
		ClientRequest request=new ClientRequest();
		request.setContent("test");
		Response response=TcpClient.send(request);
		System.out.println(response.getResult());
	}
}
